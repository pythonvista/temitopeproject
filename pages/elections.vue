<template>
  <div>
    <UtilsBannerSlider></UtilsBannerSlider>
    <div class="px-3 my-4" v-for="(i, index) in allPools" :key="index">
      <p class="text-2xl font-bold w-full text-center">
        {{ i.title }} Contestants
      </p>
      <UtilsSliderCards
        :allVotes="allVotes"
        :data="allContestant.filter((v) => v.pollsid == i.id)"
      ></UtilsSliderCards>
    </div>
  </div>
</template>
<script>
import { onSnapshot } from 'firebase/firestore';
let nuxt;
let crud;
let store;
export default {
  data: () => ({
    allElection: [],
    allPools: [],
    allContestant: [],
    allVotes: [],
    loading: false,
    ele: false,
    pls: false,
    cont: false,
    election: {},
    polls: {},
    contestant: {},
  }),
  methods: {
    GetAll() {
      onSnapshot(crud.queryDoc('ELECTIONS'), (snapshot) => {
        this.allElection = [];
        snapshot.forEach((doc) => {
          this.allElection.push(doc.data());
        });
      });
      onSnapshot(crud.queryDoc('POLLS'), (snapshot) => {
        this.allPools = [];
        snapshot.forEach((doc) => {
          this.allPools.push(doc.data());
        });
      });
      onSnapshot(crud.queryDoc('Conts'), (snapshot) => {
        this.allContestant = [];
        snapshot.forEach((doc) => {
          this.allContestant.push(doc.data());
        });
      });
      onSnapshot(crud.queryDoc('VOTES'), (snapshot) => {
        this.allVotes = [];
        snapshot.forEach((doc) => {
          this.allVotes.push(doc.data());
        });
      });
    },
  },
  created() {
    nuxt = useNuxtApp();
    crud = nuxt.$crud;
  },
  mounted() {
    this.GetAll();
  },
  setup() {
    definePageMeta({
      layout: 'home',
    });
  },
};
</script>

<style></style>

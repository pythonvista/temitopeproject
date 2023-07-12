<template>
  <div class="h-screen flex justify-center gap-4 items-center flex-col">
    <p class="text-3xl font-bold text-center">Temitope Project (matric no)</p>
    <p class="text-3xl font-bold text-center">(University)</p>
    <p class="text-3xl font-bold text-center">(Department)</p>
    <q-btn :to="{ path: '/login' }">Student Login</q-btn>
    <q-btn :to="{ path: '/register' }">Register Student</q-btn>
    <q-btn :to="{ path: '/admin' }">Admin</q-btn>
  </div>
</template>

<script>
export default {};
</script>

<style></style>

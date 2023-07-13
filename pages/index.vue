<template>
  <div>
    <header class="ud-header px-4 bg-green-700 text-white">
      <div class="">
        <div class="row">
          <div class="col-lg-12">
            <nav class="navbar navbar-expand-lg">
              <a class="navbar-brand" href="index.html">
                <!-- FUOYE NAV LOGO -->
                <img
                  class="navbar-brand-fuoye-logo"
                  src="@/assets/images/logo/fuoye-logo.png"
                  alt="Logo"
                />
              </a>
              <button class="navbar-toggler">
                <span class="toggler-icon"> </span>
                <span class="toggler-icon"> </span>
                <span class="toggler-icon"> </span>
              </button>

              <div class="navbar-collapse">
                <ul id="nav" class="navbar-nav mx-auto">
                  <li class="nav-item">
                    <a class="ud-menu-scroll" href="#home">Home</a>
                  </li>

                  <li class="nav-item">
                    <a class="ud-menu-scroll" href="#about">About</a>
                  </li>

                  <li class="nav-item">
                    <a class="ud-menu-scroll" href="#team">Team</a>
                  </li>

                  <li class="nav-item">
                    <a class="ud-menu-scroll" href="#contact">Contact</a>
                  </li>
                </ul>
              </div>

              <div class="navbar-btn d-none d-sm-inline-block">
                <a
                  @click="$router.push({ path: '/login' })"
                  class="ud-main-btn ud-login-btn"
                >
                  Sign In
                </a>
                <a
                  class="ud-main-btn ud-white-btn"
                  @click="$router.push({ path: '/register' })"
                >
                  Sign Up
                </a>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </header>
    <!-- ====== Header End ====== -->

    <!-- ====== Hero Start ====== -->
    <section style="background: green !important;" class="ud-hero px-4 min-h-screen flex justify-center items-center text-white bg-green-700" id="home">
      <div class="">
        <div class="row">
          <div class="col-lg-12">
            <div class="ud-hero-content wow fadeInUp" data-wow-delay=".2s">
              <h1 class="ud-hero-title">Fuoye E-Voting System</h1>
              <p class="ud-hero-desc">Vote for a better fuoye</p>
              <ul class="ud-hero-buttons">
                <li>
                  <a
                    @click="$router.push({ path: '/register' })"
                    rel="nofollow noopener"
                    target="_blank"
                    class="ud-main-btn ud-white-btn hover:text-black"
                  >
                    Register/Vote
                  </a>
                </li>
                <li>
                  <a
                    rel="nofollow noopener"
                    target="_blank"
                    class="ud-main-btn ud-link-btn"
                  >
                    Learn More <i class="lni lni-arrow-right"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Hero End ====== -->

    <!-- ====== Features Start ====== -->
    <section id="features" class="ud-features px-4">
      <div class="">
        <div class="row">
          <div class="col-lg-12">
            <div class="ud-section-title">
              <span>Event</span>
              <h2>Student union Election</h2>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ex,
                tempore!
              </p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-feature wow fadeInUp" data-wow-delay=".1s">
              <div class="ud-feature-icon">
                <!-- fuoye vc -->
                <img
                  src="@/assets/fuoyevc1.jpg"
                  alt=""
                />
              </div>
              <div class="ud-feature-content">
                <h3 class="ud-feature-title">Prof. Adesina</h3>
                <p class="ud-feature-desc">
                  Lorem Ipsum is simply dummy text of the printing and industry.
                </p>
                <a href="javascript:void(0)" class="ud-feature-link">
                  Learn More
                </a>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-feature wow fadeInUp" data-wow-delay=".15s">
              <div class="ud-feature-icon">
                <!-- fuoye DVC -->
                <img
                  src="@/assets/fuoyevc1.jpg"
                  alt=""
                />
              </div>
              <div class="ud-feature-content">
                <h3 class="ud-feature-title">Prof.</h3>
                <p class="ud-feature-desc">
                  Lorem Ipsum is simply dummy text of the printing and industry.
                </p>
                <a href="javascript:void(0)" class="ud-feature-link">
                  Learn More
                </a>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-feature wow fadeInUp" data-wow-delay=".2s">
              <div class="ud-feature-icon">
                <!-- HOD computer department -->

                <img
                  src="@/assets/fuoyevc1.jpg"
                  alt=""
                />
              </div>
              <div class="ud-feature-content">
                <h3 class="ud-feature-title">Dr. Sobowale</h3>
                <p class="ud-feature-desc">
                  Lorem Ipsum is simply dummy text of the printing and industry.
                </p>
                <a href="javascript:void(0)" class="ud-feature-link">
                  Learn More
                </a>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-feature wow fadeInUp" data-wow-delay=".25s">
              <div class="ud-feature-icon">
                <!--Dean of Engineering-->

                <img
                  src="@/assets/fuoyevc1.jpg"
                  alt=""
                />
              </div>
              <div class="ud-feature-content">
                <h3 class="ud-feature-title">Dean of Eng.</h3>
                <p class="ud-feature-desc">
                  Lorem Ipsum is simply dummy text of the printing and industry.
                </p>
                <a href="javascript:void(0)" class="ud-feature-link">
                  Learn More
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Features End ====== -->

    <!-- ====== About Start ====== -->
    <section id="about" class="ud-about px-4">
      <div class="">
        <div class="ud-about-wrapper wow fadeInUp" data-wow-delay=".2s">
          <div class="ud-about-content-wrapper">
            <div class="ud-about-content">
              <span class="tag">About Us</span>

              <p>
                Welcome to the FUOYE E-Voting platform, an innovative and secure
                online voting system designed to facilitate transparent and
                efficient elections within the Federal University Oye-Ekiti
                (FUOYE) community. Our E-Voting platform is dedicated to
                providing a reliable and user-friendly digital solution for
                democratic decision-making.
              </p>

              <h6>Our Vision:</h6>
              <p>
                To revolutionize the voting process at FUOYE by embracing
                technology and ensuring a fair, inclusive, and transparent
                electoral system that upholds the democratic principles of our
                institution.
              </p>
              <a href="javascript:void(0)" class="ud-main-btn">Learn More</a>
            </div>
          </div>

          <!-- voting/election illustration -->
          <div class="ud-about-image">
            <img
              src="@/assets/about-image.svg"
              alt="about-image"
            />
          </div>
        </div>
      </div>
    </section>
    <!-- ====== About End ====== -->

    <!-- ====== Team Start ====== -->
    <section id="team" class="ud-team px-4">
      <div class="">
        <div class="row">
          <div class="col-lg-12">
            <div class="ud-section-title mx-auto text-center">
              <span>Our Team</span>
              <h2>Meet The Team</h2>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vero,
                eum.
              </p>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-team wow fadeInUp" data-wow-delay=".1s">
              <div class="ud-team-image-wrapper">
                <div class="ud-team-image">
                  <img src="@/assets/images/team/team-01.png" alt="team" />
                </div>

                <img
                  src="@/assets/images/team/dotted-shape.svg"
                  alt="shape"
                  class="shape shape-1"
                />
                <img
                  src="@/assets/images/team/shape-2.svg"
                  alt="shape"
                  class="shape shape-2"
                />
              </div>
              <div class="ud-team-info">
                <h5>Adveen Desuza</h5>
                <h6>UI Designer</h6>
              </div>
              <ul class="ud-team-socials">
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-facebook-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-twitter-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-instagram-filled"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-team wow fadeInUp" data-wow-delay=".15s">
              <div class="ud-team-image-wrapper">
                <div class="ud-team-image">
                  <img src="@/assets/images/team/team-02.png" alt="team" />
                </div>

                <img
                  src="@/assets/images/team/dotted-shape.svg"
                  alt="shape"
                  class="shape shape-1"
                />
                <img
                  src="@/assets/images/team/shape-2.svg"
                  alt="shape"
                  class="shape shape-2"
                />
              </div>
              <div class="ud-team-info">
                <h5>Jezmin uniya</h5>
                <h6>Product Designer</h6>
              </div>
              <ul class="ud-team-socials">
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-facebook-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-twitter-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-instagram-filled"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-team wow fadeInUp" data-wow-delay=".2s">
              <div class="ud-team-image-wrapper">
                <div class="ud-team-image">
                  <img src="@/assets/images/team/team-03.png" alt="team" />
                </div>

                <img
                  src="@/assets/images/team/dotted-shape.svg"
                  alt="shape"
                  class="shape shape-1"
                />
                <img
                  src="@/assets/images/team/shape-2.svg"
                  alt="shape"
                  class="shape shape-2"
                />
              </div>
              <div class="ud-team-info">
                <h5>Andrieo Gloree</h5>
                <h6>App Developer</h6>
              </div>
              <ul class="ud-team-socials">
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-facebook-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-twitter-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-instagram-filled"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-sm-6">
            <div class="ud-single-team wow fadeInUp" data-wow-delay=".25s">
              <div class="ud-team-image-wrapper">
                <div class="ud-team-image">
                  <img src="@/assets/images/team/team-04.png" alt="team" />
                </div>

                <img
                  src="@/assets/images/team/dotted-shape.svg"
                  alt="shape"
                  class="shape shape-1"
                />
                <img
                  src="@/assets/images/team/shape-2.svg"
                  alt="shape"
                  class="shape shape-2"
                />
              </div>
              <div class="ud-team-info">
                <h5>Jackie Sanders</h5>
                <h6>Content Writer</h6>
              </div>
              <ul class="ud-team-socials">
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-facebook-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-twitter-filled"></i>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/MusharofChy">
                    <i class="lni lni-instagram-filled"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Team End ====== -->

    <!-- ====== Contact Start ====== -->
    <section id="contact" class="ud-contact ">
      <div class="">
        <div class="row align-items-center">
          <div class="col-xl-8 col-lg-7">
            <div class="ud-contact-content-wrapper">
              <div class="ud-contact-title">
                <span>CONTACT US</span>
                <h2>
                  Let’s talk about <br />
                  Love to hear from you!
                </h2>
              </div>
              <div class="ud-contact-info-wrapper">
                <div class="ud-single-info">
                  <div class="ud-info-icon">
                    <i class="lni lni-map-marker"></i>
                  </div>
                  <div class="ud-info-meta">
                    <h5>Our Location</h5>
                    <p>Lorem ipsum dolor sit amet.</p>
                  </div>
                </div>
                <div class="ud-single-info">
                  <div class="ud-info-icon">
                    <i class="lni lni-envelope"></i>
                  </div>
                  <div class="ud-info-meta">
                    <h5>How Can We Help?</h5>
                    <p>info@yourdomain.com</p>
                    <p>contact@yourdomain.com</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-4 col-lg-5">
            <div
              class="ud-contact-form-wrapper wow fadeInUp"
              data-wow-delay=".2s"
            >
              <h3 class="ud-contact-form-title">Send us a Message</h3>
              <form class="ud-contact-form">
                <div class="ud-form-group">
                  <label for="fullName">Full Name*</label>
                  <input type="text" name="fullName" placeholder="Joe Biden" />
                </div>
                <div class="ud-form-group">
                  <label for="email">Email*</label>
                  <input
                    type="email"
                    name="email"
                    placeholder="example@yourmail.com"
                  />
                </div>
                <div class="ud-form-group">
                  <label for="phone">Phone*</label>
                  <input
                    type="text"
                    name="phone"
                    placeholder="+234 254 5211 552"
                  />
                </div>
                <div class="ud-form-group">
                  <label for="message">Message*</label>
                  <textarea
                    name="message"
                    rows="1"
                    placeholder="type your message here"
                  ></textarea>
                </div>
                <div class="ud-form-group mb-0">
                  <button type="submit" class="ud-main-btn">
                    Send Message
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Contact End ====== -->

    <!-- ====== Footer Start ====== -->
    <footer style="background: gray !important; " class="ud-footer wow fadeInUp bg-gray-700" data-wow-delay=".15s">
      <div class="shape shape-1">
        <img src="@/assets/images/footer/shape-1.svg" alt="shape" />
      </div>
      <div class="shape shape-2">
        <img src="@/assets/images/footer/shape-2.svg" alt="shape" />
      </div>
      <div class="shape shape-3">
        <img src="@/assets/images/footer/shape-3.svg" alt="shape" />
      </div>
      <div class="ud-footer-widgets">
        <div class="">
          <div class="row">
            <div class="col-xl-3 col-lg-4 col-md-6">
              <div class="ud-widget">
                <a href="index.html" class="ud-footer-logo">
                  <img
                    class="navbar-brand-fuoye-logo"
                    src="@/assets/images/logo/fuoye-logo.png"
                    alt="logo"
                  />
                </a>
                <p class="ud-widget-desc">
                  We create digital experiences for brands and companies by
                  using technology.
                </p>
                <ul class="ud-widget-socials">
                  <li>
                    <a href="https://twitter.com/MusharofChy">
                      <i class="lni lni-facebook-filled"></i>
                    </a>
                  </li>
                  <li>
                    <a href="https://twitter.com/MusharofChy">
                      <i class="lni lni-twitter-filled"></i>
                    </a>
                  </li>
                  <li>
                    <a href="https://twitter.com/MusharofChy">
                      <i class="lni lni-instagram-filled"></i>
                    </a>
                  </li>
                  <li>
                    <a href="https://twitter.com/MusharofChy">
                      <i class="lni lni-linkedin-original"></i>
                    </a>
                  </li>
                </ul>
              </div>
            </div>

            <div class="col-xl-2 col-lg-2 col-md-6 col-sm-6">
              <div class="ud-widget">
                <h5 class="ud-widget-title">About Us</h5>
                <ul class="ud-widget-links">
                  <li>
                    <a href="javascript:void(0)">Home</a>
                  </li>
                  <li>
                    <a href="javascript:void(0)">Features</a>
                  </li>
                  <li>
                    <a href="javascript:void(0)">About</a>
                  </li>
                  <li>
                    <a href="javascript:void(0)">Testimonial</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-xl-2 col-lg-3 col-md-6 col-sm-6">
              <div class="ud-widget">
                <h5 class="ud-widget-title">Features</h5>
                <ul class="ud-widget-links">
                  <li>
                    <a href="javascript:void(0)">How it works</a>
                  </li>
                  <li>
                    <a href="javascript:void(0)">Privacy policy</a>
                  </li>
                  <li>
                    <a href="javascript:void(0)">Terms of service</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="ud-footer-bottom">
        <div class="">
          <div class="row">
            <div class="col-md-8">
              <ul class="ud-footer-bottom-left">
                <li>
                  <a href="javascript:void(0)">Privacy policy</a>
                </li>
                <li>
                  <a href="javascript:void(0)">Support policy</a>
                </li>
                <li>
                  <a href="javascript:void(0)">Terms of service</a>
                </li>
              </ul>
            </div>
            <div class="col-md-4">
              <p class="ud-footer-bottom-right">
                Designed and Developed by
                <a href="https:" rel="nofollow">TGC</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  setup() {
    useHead({
      script: [
         {
          src: 'https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js',
          type: 'text/javascript',
          async: true,
        },
        {
          src: 'https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js',
          type: 'text/javascript',
          async: true,
        },
      ]
    })
  }
};
</script>

<style scoped>
@import '@/assets/css/ud-styles.css';
</style>
<style scoped>
@import '@/assets/css/style.css';
</style>
<style scoped>
@import '@/assets/css/animate.css';
</style>
<style scoped>
@import '@/assets/css/bootstrap.min.css';
</style>
<style scoped>
@import '@/assets/css/lineicons.css';
</style>

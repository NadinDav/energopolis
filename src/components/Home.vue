<template>
  <Navbar />
  <Header />
  <About />

  <div class="bg-grey-50 py-5 page-section">
    <div class="container">
      <div
        class="flex flex-col lg:flex-row items-center justify-evenly space-x-3 h-full text-left py-5">
        <lottie-player
              src="https://assets8.lottiefiles.com/packages/lf20_sfcrjow9.json"
              background="transparent"
              speed="1"
              style="max-width: 500px; max-height: 500px"
              autoplay></lottie-player>

              <lottie-player
              src="https://assets8.lottiefiles.com/packages/lf20_hjn3zzgy.json"
              background="transparent"
              speed="1"
              style="max-width: 500px; max-height: 500px"
              autoplay></lottie-player>

              <lottie-player
              src="https://assets8.lottiefiles.com/packages/lf20_tr1pjkop.json"
              background="transparent"
              speed="1"
              style="max-width: 500px; max-height: 500px"
              autoplay></lottie-player>
      </div>
    </div>
  </div>

  <Footer />
</template>

<script>
import Navbar from "./Navbar.vue";
import Header from "./Header.vue";
import About from "./About.vue";
import Footer from "./Footer.vue";

export default {
  name: "Home",
  data() {
    return {};
  },

  props: {
    blog: Array,
  },

  components: {
    Navbar,
    Header,
    About,
    Footer,
  },
};
</script>

<style></style>

<template>
  <Navbar />
  <About />
  <Footer />
</template>

<script>
import Navbar from "../components/Navbar";
import About from "../components/About";
import Footer from "../components/Footer";

export default {
  name: "About Page",
  data() {
    return {};
  },

  props: {
    blog: Array,
  },

  components: {
    Navbar,
    About,
    Footer,
  },
};
</script>

<style></style>

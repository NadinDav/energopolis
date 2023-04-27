<template>
  <Navbar />
  <Footer />
</template>

<script>
import Navbar from "./Navbar.vue";
import Footer from "./Footer.vue";

export default {
  name: "Single Project Page",
  data() {
    return {
      project: ProjectData,
    };
  },
  props: {
    blog: Array,
  },
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style></style>

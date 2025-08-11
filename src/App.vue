<template>
  <Navbar />
  <Intro />
  <About />
  <Technologies />
</template>

<script>
import About from "./components/About.vue";
import Intro from "./components/Intro.vue";
import Navbar from "./components/Navbar.vue";
import Technologies from "./components/Technologies.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Intro,
    About,
    Technologies,
  },
};
</script>

<style>
* {
  font-family: "Inter", sans-serif;
}
</style>

<template>
  <Navbar />
  <Intro />
  <About />
</template>

<script>
import About from "./components/About.vue";
import Intro from "./components/Intro.vue";
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Intro,
    About,
  },
};
</script>

<style>
* {
  font-family: "Inter", sans-serif;
}
</style>

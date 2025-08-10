<template>
  <Navbar />
  <Intro />
</template>

<script>
import Intro from "./components/Intro.vue";
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Intro,
  },
};
</script>

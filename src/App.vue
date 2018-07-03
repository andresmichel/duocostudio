<template>
  <div id="app">
    <Navbar />
    <Carousel />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Carousel from "./components/Carousel.vue";

export default {
  name: "app",
  components: {
    Navbar,
    Carousel
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  margin: 0;
}
</style>

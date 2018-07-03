<template>
  <div id="app">
    <Work />
  </div>
</template>

<script>
import Work from "./components/Work.vue";

export default {
  name: "app",
  components: {
    Work
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
  margin-top: 60px;
}
</style>

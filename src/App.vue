<template>
  <div id="app">
    <Navbar />
    <Welcome />
    <Work />
    <!-- <Contact /> -->
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Welcome from "./components/Welcome.vue";
import Work from "./components/Work.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Navbar,
    Welcome,
    Work,
    Contact,
    Footer
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

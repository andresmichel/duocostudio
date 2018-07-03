<template>
    <div class="carousel">
        <Work />
        <Work />
        <Work />
        <Work />
    </div>
</template>

<script>
import Work from "./Work.vue";

export default {
  name: "Carousel",
  components: {
    Work
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.carousel {
  display: flex;
  position: absolute;
  top: 0;
  left: 0;
  height: 100vh;
  width: 100vw;
}
</style>

<template>
  <div class="navbar">
    <div class="container">
      <div class="row">
        <div class="col logo">
          <img src="../assets/logo.svg" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  display: flex;
  position: fixed;
  align-items: center;
  top: 0;
  width: 100vw;
  height: 70px;
  background-color: #fff;
  z-index: 1;
}
.navbar .logo img {
  height: 24px;
}
</style>

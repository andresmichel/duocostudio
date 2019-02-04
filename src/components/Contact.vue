<template>
    <div class="contact">
      <a href="mailto:hola@duocostudio.com"><i data-feather="send"></i>&nbsp;Contact us</a>
    </div>
</template>

<script>
export default {
  name: "contact",
  mounted() {
    window.feather.replace();
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.contact {
  height: 500px;
  background-color: #eee;
}
a {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

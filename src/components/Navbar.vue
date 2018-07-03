<template>
    <ul class="navbar">
        <li class="logo">
            <a href="">Duoco</a>
        </li>
        <li>
            <a href="">Agency</a>
        </li>
        <li>
            <a href="">Work</a>
        </li>
        <li>
            <a href="">Contact</a>
        </li>
    </ul>
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
  padding: 20px 0;
  width: 100vw;
  margin: 0;
  list-style: none;
  z-index: 1;
  background-color: #fff;
  border-bottom: 1px solid #aaa;
}
.navbar li {
  padding: 0 30px;
}
.navbar li a {
  text-decoration: none;
  color: #000;
}
.navbar li a {
  text-decoration: none;
  color: #000;
}
.navbar .logo {
  margin-right: auto;
}
</style>

<template>
    <div class="welcome">
      <div class="container">
        <div class="row">
          <div class="col text-left">
            <h1>Un gran diseño<br>trae grandes resultados.</h1>
            <div class="divider"></div>
            <h4>Agencia creativa</h4>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "welcome"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.welcome {
  margin-top: 70px;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: center;
}
h1 {
  font-size: 3.5em;
}
h4 {
  color: #aaa;
}
.divider {
  margin: 50px 0;
  height: 2px;
  width: 150px;
  background-color: #ddd;
}
</style>

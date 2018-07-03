<template>
    <div class="work">
        Work
    </div>
</template>

<script>
export default {
  name: "Work"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.work {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border-right: 1px solid #aaa;
  border-bottom: 1px solid #aaa;
}
.work:last-child {
  border-right: none;
}
</style>

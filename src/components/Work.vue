<template>
    <div class="work">
      <div class="container-fluid">
        <div class="row">
          <div v-for="(item, key) in items" :key="key" class="col-12 col-sm-6 col-md-4 work-item" :style="{ backgroundImage: `url(${item.url})` }">
            <div class="work-info">{{ item.name }}</div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "work",
  data: () => ({
    items: [
      {
        name: "Kale Yeah! 360 Juices",
        url: require("../assets/dribbble-1.jpg")
      },
      {
        name: "Indan Local Coffee Packaging",
        url: require("../assets/dribbble-2.jpg")
      },
      {
        name: "Indan Local Coffee Logo",
        url: require("../assets/dribbble-3.jpg")
      },
      {
        name: "Bravana",
        url: require("../assets/dribbble-4.jpg")
      },
      {
        name: "Bravana",
        url: require("../assets/dribbble-5.jpg")
      },
      {
        name: "Sounds Good",
        url: require("../assets/dribbble-6.jpg")
      }
    ]
  })
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.work-item {
  height: 300px;
  background-position: center;
  background-size: cover;
}
.work-info {
  font-size: 1.2em;
  opacity: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  width: calc(100% + 30px);
  padding: 10px;
  margin-left: -15px;
  color: #fff;
  background-color: rgba(0, 0, 0, 0.75);
  transition: opacity 0.3s;
}
.work-item:hover .work-info {
  opacity: 1;
}
</style>

<template>
    <div class="footer">
      <div class="container">
        <div class="row">
          <div class="col-12 col-sm-6 text-left">
            Copyright of Duoco Studio 2018. All Rights Reserved.
          </div>
          <div class="col-12 col-sm-6 text-right">
            <a target="_blank" href="https://www.facebook.com/duocostudio/"><span class="social-icon"><i data-feather="facebook"></i></span></a>
            <a target="_blank" href="https://www.instagram.com/duocostudio/"><span class="social-icon"><i data-feather="instagram"></i></span></a>
            <!-- <a target="_blank" href="https://dribbble.com/duocostudio/"><span class="social-icon"><i data-feather="briefcase"></i></span></a> -->
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "footer-component",
  mounted() {
    window.feather.replace();
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  height: 150px;
  color: #fff;
  background-color: #000;
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.social-icon {
  display: inline-block;
  margin-left: 20px;
}
a {
  color: #fff;
}
a:hover {
  opacity: 0.75;
}
</style>

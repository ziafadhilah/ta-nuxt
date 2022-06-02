<template>
  <div class="app">
    <a name="home"></a>
    <Header />
    <Home />
    <a href="#" class="float">
      <img src="~/assets/images/arrow-up.png" class="my-float" />
    </a>
    <a name="about"></a>
    <About />
    <a name="our-services"></a>
    <Our-services />
    <a name="our-work"></a>
    <Our-work />
    <a name="our-clients"></a>
    <Our-clients />
    <a name="need-something"></a>
    <Need-something />
    <Footer />
  </div>
</template>
<style scoped>
.app {
  background: #f3f3f3;
}
.float {
  position: fixed;
  width: 60px;
  height: 60px;
  bottom: 40px;
  right: 40px;
  background-color: #f79b22;
  color: #fff;
  border-radius: 50px;
  text-align: center;
  box-shadow: 2px 2px 3px #999;
}

.my-float {
  margin-top: 11px;
}
@media screen and (max-width: 1280px) {
  .float {
    position: fixed;
    width: 60px;
    height: 60px;
    bottom: 40px;
    right: 40px;
    background-color: #f79b22;
    color: #fff;
    border-radius: 50px;
    text-align: center;
    box-shadow: 2px 2px 3px #999;
  }

  .my-float {
    margin-top: 11px;
  }
}
</style>
<script>
export default {
  mounted() {
    console.log("router", this.$route);
  },
};
</script>

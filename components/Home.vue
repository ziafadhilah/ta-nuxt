<template>
  <div id="home">
    <div class="container">
      <div class="row">
        <div class="col-lg-5">
          <a class="we-are">WE&nbsp;ARE</a><b class="code"> CODE</b
          ><b class="lite">LITE</b><br />
          <p class="this-text">
            <b>CODE</b>LITE has extensive app development experience of over 6
            years on all modern platforms.
          </p>
        </div>
        <div class="col-lg-7 mt-3">
          <img src="~/assets/images/home/pc.png" class="image" />
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
/* .container {
  width: 100%;
  height: 600px;
  overflow: hidden;
} */
#home {
  background-image: url("~/assets/images/home/background-test.png");
  background-size: 100% 100%;
  background-repeat: no-repeat;
  overflow: hidden;
}
.we-are {
  color: #f8fcff;
  text-decoration: none;
  font-size: xxx-large;
  font-family: "Roboto", serif;
}
.code {
  color: #f79b22;
  font-size: xxx-large;
  font-family: "Roboto", serif;
}
.lite {
  color: #f4b918;
  font-size: xxx-large;
  font-family: "Roboto", serif;
}
.this-text {
  font-size: 20px;
  font-family: "Roboto", serif;
  color: white;
}
.row {
  margin-top: 7rem;
  margin-bottom: 10rem;
}
.image {
  width: 100%;
  height: auto;
}
@media screen and (max-width: 1280px) {
  .home {
    background-image: url("~/assets/images/home/background-test.png");
    background-size: 100% auto;
    background-repeat: no-repeat;
  }
  .we-are {
    color: white;
    text-decoration: none;
    font-size: x-large;
    font-family: "Roboto", serif;
    padding: 0.5rem;
  }
  .code {
    color: #f79b22;
    font-size: x-large;
    font-family: "Roboto", serif;
  }
  .lite {
    color: #f4b918;
    font-size: x-large;
    font-family: "Roboto", serif;
  }
  .this-text {
    color: white;
    font-size: 15px;
    font-family: "Roboto", serif;
    height: 130px;
    padding: 0.5rem;
  }
  .image {
    display: none;
  }
  .row {
    margin-top: 2rem;
    margin-bottom: 0rem;
  }
}
</style>
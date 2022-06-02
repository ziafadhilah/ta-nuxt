<template>
  <div id="our-service">
    <div class="container p-3 text-center">
      <section>
        <div class="col-md-12">
          <div class="row">
            <div class="col-md-3 text-end mt-1">
              <img
                src="~/assets/images/our-services/component.png"
                class="component"
              />
            </div>
            <div class="col-md-6 text-center">
              <p class="our-services">OUR SERVICES AND EXPERTISE</p>
            </div>
            <div class="col-md-3 text-start">
              <img
                src="~/assets/images/our-services/component.png"
                class="component"
              />
            </div>
          </div>
        </div>
        <div class="row items">
          <div class="col-md-4 mb-3">
            <a href="/software-development"
              ><img
                src="~/assets/images/our-services/software.png"
                class="image w-75"
            /></a>
          </div>
          <div class="col-md-4 mb-3">
            <a href="/mobile-development">
              <img
                src="~/assets/images/our-services/mobile.png"
                width="85%"
                class="image w-75"
            /></a>
          </div>
          <div class="col-md-4 mb-3">
            <a href="/education-community">
              <img
                src="~/assets/images/our-services/education.png"
                width="85%"
                class="image w-75"
            /></a>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<style scoped>
#our-service {
  background-image: url("~/assets/images/our-services/background.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  /* background: #5b7e74; */
}
section {
  margin-bottom: 10rem;
  margin-top: 3rem;
}
.component {
  width: 50px;
}
.items {
  margin-top: 4rem;
}
.our-services {
  font-size: 35px;
  color: white;
  font-family: "Roboto", serif;
  font-weight: bold;
}
.button-our-service {
  background-color: transparent;
  border: solid;
  color: white;
  padding: 5px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  margin: 2px 2px;
  cursor: pointer;
  border-radius: 20px;
}
.button-our-service:hover {
  background-color: black;
}
.mb-5 {
  margin-bottom: 10rem !important;
}
.image:hover {
  transform: scale(1.1);
  cursor: pointer;
}
@media screen and (max-width: 1280px) {
  .component {
    width: 0px;
    text-align: center;
  }
  .our-services {
    font-size: 24px;
  }
  section {
    margin-bottom: 0rem;
    margin-top: 0rem;
  }
  .items {
    margin-top: 1rem;
  }
}
</style>
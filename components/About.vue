<template>
  <div id="about">
    <div class="container p-3">
      <section>
        <div class="row">
          <div class="col-lg-6 mb-2">
            <img
              src="~/assets/images/about/about-content.png"
              class="img-fluid"
            />
          </div>
          <div class="col-lg-6 mb-4 text-white">
            <div class="d-border p-4">
              <p class="text-break fw-normal">
                <b>CODE</b>LITE has extensive app development experience of over
                6 years on all modern platforms.
              </p>
              <p class="text-break fw-normal">
                We help you to create and build awesome web, desktop and mobile
                apps for your users, whether it’s for public or internal usage.
                Apps will be created with great experiences, easily adapted for
                all devices and screen sizes in minimum cost and timeline.
              </p>
              <p class="text-break fw-normal">
                Your future apps will be functional, yet have a good looking
                interface to show off.
              </p>
            </div>
            <a class="btn mt-4" href="#need-something">CONTACT US</a>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>
<style scoped>
#about {
  background: #f3f3f3;
}

.d-border {
  border-radius: 20px 20px 20px 20px;
  -webkit-border-radius: 20px 20px 20px 20px;
  -moz-border-radius: 20px 20px 20px 20px;
  background-color: #4b545d;
  box-shadow: 0px 2px 15px 0px rgba(0, 0, 0, 1);
  -webkit-box-shadow: 0px 2px 15px 0px rgba(0, 0, 0, 1);
  -moz-box-shadow: 0px 2px 15px 0px rgba(0, 0, 0, 1);
  font-family: "Roboto", serif;
  font-size: 18px;
}
.fw-light {
  text-decoration: none;
  color: white;
}
.btn {
  background-color: #f4b918;
  color: white;
  border-radius: 13px;
  font-family: "Roboto", serif;
  font-size: 13px;
  font-weight: bold;
}
.btn:hover {
  background-color: #f58732;
  color: white;
}
section {
  margin-top: 3rem !important;
}
@media screen and (max-width: 1280px) {
  .d-border {
    text-align: justify;
    font-size: 15px;
  }
}
</style>

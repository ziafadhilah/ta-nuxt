<template>
  <footer class="text-white" style="background-color: #3c3d3e">
    <section class="mb-4 p-4">
      <div class="container p-3">
        <div class="row">
          <div class="cluster col-lg-5 mb-4">
            <h5 class="text-uppercase">CONTACT US</h5>
            <br />
            Cluster Crystal Commercial No.8, <br />
            Summarecon Bandung, Indonesia 40296 <br />
            office@codelite.id <br />
            081234567890
          </div>
          <div class="col-lg-5 mb-4">
            <h5 class="text-uppercase">menu</h5>
            <br />
            <ul class="list-unstyled mb-0 fw-light">
              <li>
                <a href="#home" class="text-white">HOME</a>
              </li>
              <li>
                <a href="/team" class="text-white">TEAM</a>
              </li>
              <li>
                <a href="#our-services" class="text-white">SERVICE</a>
              </li>
              <li>
                <a href="#our-work" class="text-white">OUR WORKS</a>
              </li>
              <li>
                <a href="#our-clients" class="text-white">CLIENT</a>
              </li>
              <li>
                <a href="#about" class="text-white">ABOUT US</a>
              </li>
            </ul>
          </div>
          <div class="col-lg-2 mb-4">
            <h5 class="text-uppercase">FOLLOW US</h5>
            <br />
            <div class="row mb-2">
              <div class="col-lg-4">
                <img
                  src="~/assets/images/footer/linkedin.png"
                  class="image"
                  width="100%"
                />
              </div>
              <div class="col p-2">LinkedIn</div>
            </div>
            <div class="row mb-2">
              <div class="col-lg-4">
                <img
                  src="~/assets/images/footer/facebook.png"
                  class="image"
                  width="100%"
                />
              </div>
              <div class="col p-2">Facebook</div>
            </div>
            <div class="row">
              <div class="col-lg-4">
                <img
                  src="~/assets/images/footer/instagram.png"
                  class="image"
                  width="100%"
                />
              </div>
              <div class="col p-2">Instagram</div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div
      class="copyright text-center p-3"
      style="background: #1f1d1b; font-size: 14px"
    >
      Copyright 2022 &copy; PT CAHAYA ACITYA INDONESIA
    </div>
  </footer>
</template>
<style scoped>
.row {
  font-family: "Roboto", serif;
}
a {
  text-decoration: none;
}
h5 {
  font-family: "Roboto", serif;
  font-weight: bold;
  font-size: 20px;
}
li {
  font-family: "Roboto", serif;
  font-size: 15px;
}
.cluster {
  font-family: "Roboto", serif;
  font-size: 15px;
}
.copyright {
  font-family: "Roboto", serif;
}
@media screen and (max-width: 1280px) {
  .image {
    width: 15%;
  }
  h5 {
    text-align: center;
  }
  li {
    text-align: center;
  }
  .col-lg-4 {
    text-align: center;
  }
  .col {
    text-align: center;
  }
  .cluster {
    text-align: center;
  }
}
</style>
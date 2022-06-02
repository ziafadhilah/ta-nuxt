<template>
  <div class="app" style="background: #f3f3f3">
    <header>
      <nav class="navbar navbar-expand-lg sticky-top fw-light">
        <div class="container">
          <a class="navbar-brand p-2" href="/"
            ><img src="~/assets/images/logocodelite.png" width="50px"
          /></a>
          <button
            class="navbar-toggler navbar-dark"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-center" id="navbarNav">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="/">HOME</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/#about">ABOUT</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/#our-service">SERVICE</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/career">CAREER</a>
              </li>
              <!-- <li class="nav-item">
              <a class="nav-link" href="#our-clients">CLIENTS</a>
            </li> -->
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="navbarDarkDropdownMenuLink"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                  >OUR WORKS</a
                >
                <ul
                  class="dropdown-menu dropdown-menu-light fw-light"
                  style="background: #f3f3f3"
                >
                  <li>
                    <a class="dropdown-item" href="/kemkominfo"
                      >Sap Kemkominfo RI</a
                    >
                  </li>
                  <li>
                    <a class="dropdown-item" href="/tree-apps"
                      >TREE Apps - Echomacther</a
                    >
                  </li>
                  <li>
                    <a class="dropdown-item" href="/jaraya"
                      >JARAYA Mobile Apps</a
                    >
                  </li>
                  <li>
                    <a class="dropdown-item" href="/cgo">CGO Mobile Apps</a>
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/team">TEAM</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <div class="container p-4 text-center">
      <div class="col-lg-12">
        <img src="~/assets/images/team.png" width="100%" />
      </div>
      <div class="d-flex justify-content-center mt-4">
        <div class="strike">
          <span
            ><h3><b>THIS IS A HEADLINE</b></h3></span
          >
        </div>
      </div>
      <div class="col-lg-12 p-4 m-3 mt-4 text-center">
        <div class="row">
          <div class="col-lg-3 mb-3">
            <img src="~/assets/images/eren.png" class="avatar mb-3" />
            <h5 class="mb-3">
              Eren Yaeger
              <p class="mt-2">Chairman</p>
            </h5>
          </div>
          <div class="col-lg-3 mb-3">
            <img src="~/assets/images/levi.png" class="avatar mb-3" />
            <h5 class="mb-3">
              Levi Ackerman
              <p class="mt-2">CEO</p>
            </h5>
          </div>
          <div class="col-lg-3 mb-3">
            <img src="~/assets/images/mikasa.png" class="avatar mb-3" />
            <br />
            <h5 class="mb-3">
              Mikasa Ackerman
              <p class="mt-2">CTO</p>
            </h5>
          </div>
          <div class="col-lg-3 mb-3">
            <img src="~/assets/images/armin.png" class="avatar mb-3" />
            <br />
            <h5 class="mb-3">
              Armin Arlert
              <p class="mt-2">CFO</p>
            </h5>
          </div>
        </div>
      </div>
    </div>
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
                  <a href="/" class="text-white">HOME</a>
                </li>
                <li>
                  <a href="#" class="text-white">TEAM</a>
                </li>
                <li>
                  <a href="/#our-services" class="text-white">SERVICE</a>
                </li>
                <li>
                  <a href="/#our-work" class="text-white">OUR WORKS</a>
                </li>
                <li>
                  <a href="/#client" class="text-white">CLIENT</a>
                </li>
                <li>
                  <a href="/#about" class="text-white">ABOUT US</a>
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
        style="background-color: rgba(31, 29, 27, 100%); font-size: 14px"
      >
        Copyright 2022 &copy; PT CAHAYA ACITYA INDONESIA
      </div>
    </footer>
  </div>
</template>
<style scoped>
.navbar {
  background: #4b545d;
  box-shadow: 0px 1px 3px -1px rgba(0, 0, 0, 0.35);
  -webkit-box-shadow: 0px 1px 3px -1px rgba(0, 0, 0, 0.35);
  -moz-box-shadow: 0px 1px 3px -1px rgba(0, 0, 0, 0.35);
}
.nav-link {
  width: 110px;
  font-size: 15px;
  font-family: "Roboto", serif;
  color: white;
}
.nav-link:hover {
  /* background-color: white; */
  box-shadow: inset 0 -1px 0 0 #f79b22;
  color: #f79b22;
  /* width: 120px; */
}
.dropdown-menu {
  font-size: 15px;
  font-family: "Roboto", serif;
  box-shadow: 2px 5px 8px -5px rgba(0, 0, 0, 0.43);
  -webkit-box-shadow: 2px 5px 8px -5px rgba(0, 0, 0, 0.43);
  -moz-box-shadow: 2px 5px 8px -5px rgba(0, 0, 0, 0.43);
}
.dropdown-item:hover {
  box-shadow: inset 0 -1px 0 0 #f79b22;
  background: #f3f3f3;
  color: #f79b22;
}
.cluster {
  font-family: "Roboto", serif;
  font-size: 15px;
}
.avatar {
  object-fit: cover;
  border-radius: 50%;
  width: 150px;
  height: 150px;
}
.mt-5 {
  margin-top: 5rem !important;
}
a {
  text-decoration: none;
}
li {
  font-family: "Roboto", serif;
  font-size: 15px;
}
h5,
h3 {
  font-family: "Roboto", serif;
}
.strike > span {
  position: relative;
  display: inline-block;
}

.strike > span:before,
.strike > span:after {
  content: "";
  position: absolute;
  top: 37%;
  width: 405px;
  height: 1px;
  box-shadow: 1px 1px 18px 0px rgba(0, 0, 0, 0.75);
  -webkit-box-shadow: 1px 1px 18px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 1px 1px 18px 0px rgba(0, 0, 0, 0.75);
  background: #3e3e3f;
}

.strike > span:before {
  right: 100%;
  margin-right: 15px;
}

.strike > span:after {
  left: 100%;
  margin-left: 15px;
}

@media screen and (max-width: 1280px) {
  footer {
    text-align: center;
    font-family: "Roboto", serif;
  }
  .nav-link {
    width: 0px;
    font-family: "Roboto", serif;
  }
  .image {
    width: 20%;
  }
  h5 {
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
  .strike > span:before,
  .strike > span:after {
    content: "";
    position: absolute;
    top: 37%;
    width: 0px;
    height: 1px;
    box-shadow: 1px 1px 18px 0px rgba(0, 0, 0, 0.75);
    -webkit-box-shadow: 1px 1px 18px 0px rgba(0, 0, 0, 0.75);
    -moz-box-shadow: 1px 1px 18px 0px rgba(0, 0, 0, 0.75);
    background: #3e3e3f;
  }
  .strike > span:before {
    right: 100%;
    margin-right: 15px;
  }

  .strike > span:after {
    left: 100%;
    margin-left: 15px;
  }
}
</style>
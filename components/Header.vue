<template>
  <header>
    <nav class="navbar navbar-expand-lg sticky-top fw-light">
      <div class="container">
        <a class="navbar-brand p-2" href="#home"
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
              <a class="nav-link" aria-current="page" href="#home">HOME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">ABOUT</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#our-services">SERVICE</a>
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
                  <a class="dropdown-item" href="/jaraya">JARAYA Mobile Apps</a>
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
</template>
<style scoped>
.navbar {
  background: #4b545d;
  box-shadow: 0px 1px 3px -1px rgba(0, 0, 0, 0.35);
  -webkit-box-shadow: 0px 1px 3px -1px rgba(0, 0, 0, 0.35);
  -moz-box-shadow: 0px 1px 3px -1px rgba(0, 0, 0, 0.35);
}
.nav-link {
  width: 105px;
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
@media screen and (max-width: 1280px) {
  .nav-link {
    width: 0px;
    font-family: "Roboto", serif;
  }
}
</style>
<template>
  <section class="p-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 mb-3">
          <h3>
            DO YOU NEED <br />
            SOMETHING?
          </h3>
          <br />
          <h5>COME TELL US!</h5>
        </div>
        <div class="col-lg-2 mb-4">
          <img
            src="~/assets/images/need-something/people.png"
            class="img-fluid"
          />
        </div>
        <div class="col-lg-6">
          <div class="input-group mb-3">
            <input type="text" placeholder="Your Name*" class="form-control" />
          </div>
          <div class="row">
            <div class="col-lg-6">
              <div class="input-group mb-3">
                <input type="email" placeholder="Email*" class="form-control" />
              </div>
            </div>
            <div class="col-lg-6">
              <div class="input-group mb-3">
                <input
                  type="number"
                  placeholder="Phone Number*"
                  class="form-control"
                />
              </div>
            </div>
          </div>
          <div class="form-floating mb-3">
            <input
              type="text"
              class="form-control"
              placeholder="Your Message*"
              style="height: 150px"
              id="floatingInput"
            />
            <label class="float" for="floatingInput">Your Message*</label>
          </div>
          <div class="text-center">
            <button class="submit">SUBMIT</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
section {
  background-image: url("~/assets/images/need-something/background.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.submit {
  background-color: #f3aa02;
  border: none;
  color: white;
  padding: 5px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  margin: 2px 2px;
  cursor: pointer;
  border-radius: 12px;
  font-family: "Roboto", serif;
  font-weight: bold;
}
.submit:hover {
  background-color: #f58732;
  color: white;
}
.form-control {
  background-color: #f3f3f3;
  color: #3e3e3f;
  border: none;
  border-radius: 10px;
}
::placeholder {
  color: #3e3e3f;
}
.float {
  color: #3e3e3f;
}
h3 {
  font-family: "Roboto", serif;
  font-size: xx-large;
  color: white;
}
h5 {
  font-size: x-large;
  font-family: "Roboto", serif;
  color: white;
}
.img-fluid {
  width: 75%;
}
@media screen and (max-width: 1280px) {
  .img-fluid {
    display: none;
  }
  h3 {
    font-family: "Roboto", serif;
    font-size: 24px;
    color: white;
  }
  h5 {
    font-size: 24px;
    font-family: "Roboto", serif;
    color: white;
  }
  .submit {
    font-size: 15px;
  }
}
</style>
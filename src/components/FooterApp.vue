<template>
  <div class="container-fluid d-flex justify-content-center">
    <div class="row">
      <div class="col-6">
        <div class="upper-footer">
          <h1 class="awesome">We Offer Awesome Services</h1>
          <p class="awesome-p">
            When, while the lovely valley teams with vapour around meand the
            meridian sun strikes the upper surface.
          </p>
          <input class="input" type="email-input" /><button
            class="email-subscribe"
          >
            Subscribe
          </button>
          <span class="email">Enter Your email address</span>
        </div>
      </div>
    </div>
    <!-- <div class="bottom-footer">
      <div class="container">
        <div class="row">
          <div class="col-12"></div>
        </div>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: "FooterApp",
};
</script>

<style lang="scss" scoped>
.upper-footer {
  width: 1300px;
  height: 200px;
  border-radius: 30px;
  background-color: #d3406d;
}

.awesome {
  color: white;
  text-align: left;
  font-size: 50px;
  font-weight: 900;
  margin-top: 50px;
  margin-left: 30px;
}

.awesome-p {
  color: white;
  text-align: left;
  margin-top: 20px;
  margin-left: 30px;
}

.input {
  float: right;
  width: 420px;
  height: 60px;
  margin-top: -100px;
  margin-right: 20px;
  border-radius: 30px;
}

.email-subscribe {
  float: right;
  width: 130px;
  height: 40px;
  margin-top: -89px;
  margin-right: 40px;
  border-radius: 30px;
  color: white;
  font-weight: 700;
  background-color: #2078bb;
}

.email {
  float: right;
  margin-top: -82px;
  margin-right: 200px;
  color: rgb(163, 162, 162);
  font-size: 20px;
}

.bottom-footer {
  width: 100%;
  height: 500px;
  border: 1px solid black;
}
</style>
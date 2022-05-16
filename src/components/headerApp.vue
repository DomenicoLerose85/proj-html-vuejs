<template>
  <div class="header">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12">
          <img
            class="logo"
            src="../assets/corporate-landing/images/white-logo-2.png"
            alt="logo"
          />
          <button class="sign">Sign In</button>
          <img
            src="../assets/corporate-landing/images/header.png"
            alt="header-img"
          />
          <h1 class="title1">Business Planning</h1>
          <h2 class="title2">Digital technology</h2>
          <h3 class="title3">Modern Solution !</h3>
          <p class="sun_strikes">
            When, while the lovely valley teams with vapour around <br />meand
            the meridian sun strikes the upper surface.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderApp",
  props: {},
};
</script>


<style  lang="scss">
.header {
  width: 100%;
  background-color: #04174d;
}

.logo {
  width: 135px;
  height: 65px;
  margin-left: 90px;
  margin-top: 30px;
}

.sign {
  width: 80px;
  float: right;
  margin-top: 40px;
  margin-right: 30px;
  border-radius: 30px;
  color: white;
  background-color: rgb(38, 38, 230);
  border-color: blue;
}

img {
  width: 550px;
  height: 550px;
  // float: right;
  margin-left: 470px;
  margin-top: 30px;
}

.title1 {
  color: white;
  font-weight: bold;
  margin-top: 0px;
  margin-left: 90px;
}

.title2 {
  color: white;
  margin-top: 5px;
  margin-left: 90px;
}

.title3 {
  color: white;
  margin-top: 5px;
  margin-left: 90px;
  font-weight: 900;
  font-size: 35px;
}

.sun_strikes {
  margin-top: 20px;
  margin-left: 90px;
  color: rgb(26, 26, 172);
}
</style>

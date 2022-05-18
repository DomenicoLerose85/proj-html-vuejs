<template>
  <div class="header">
    <div class="container-fluid">
      <div class="row">
        <div class="col-6">
          <img
            class="logo"
            src="../assets/corporate-landing/images/white-logo-2.png"
            alt="logo"
          />
        </div>
      </div>
      <div class="row">
        <div class="col-6">
          <button class="sign">Sign In</button>
          <img
            src="../assets/corporate-landing/images/header.png"
            alt="header-img"
          />
        </div>
        <h1 class="title1">Business Planning</h1>
        <h2 class="title2">Digital technology</h2>
        <h3 class="title3">Modern Solution !</h3>
        <p class="sun_strikes">
          When, while the lovely valley teams with vapour around <br />meand the
          meridian sun strikes the upper surface.
        </p>
        <div class="buttons">
          <img
            class="try"
            src="../assets/corporate-landing/btn-try-now-hover.png"
            alt="try_btn"
          />
          <img
            class="explore"
            src="../assets/corporate-landing/btn-explore-hover.png"
            alt="explore_btn"
          />
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


<style  lang="scss" scoped>
.header {
  width: 100%;
  background-color: #04174d;
}

.logo {
  width: 135px;
  height: 65px;
  float: left;
  margin-left: 90px;
  margin-top: 30px;
}

.sign {
  width: 80px;
  float: right;
  margin-top: -55px;
  margin-right: -510px;
  border-radius: 30px;
  color: white;
  background-color: #1465a0;
  border-color: blue;
}

.sign:hover {
  background-color: #d3406d;
}

img {
  width: 550px;
  height: 550px;
  margin-left: 550px;
  margin-top: 30px;
}

.title1 {
  color: white;
  font-weight: bold;
  margin-top: -295px;
  margin-left: 0px;
}

.title2 {
  color: white;
  margin-top: -230px;
  margin-left: 2px;
}

.title3 {
  color: white;
  margin-top: -185px;
  margin-left: 2px;
  font-weight: 900;
  font-size: 35px;
}

.sun_strikes {
  margin-top: -120px;
  margin-left: 4px;
  color: rgb(26, 26, 172);
  font-weight: bold;
}

.try {
  width: 150px;
  height: 80px;
  margin-right: 260px;
  margin-bottom: 50px;
}

.explore {
  display: inline-block;
  width: 150px;
  height: 80px;
  margin-right: 680px;
  margin-top: -129px;
}
</style>

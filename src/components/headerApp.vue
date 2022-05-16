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
        </div>
        <div class="col-6 d-flex justify-content-start">
          <h1 class="title1">Business Planning</h1>
          <h2 class="title2">Digital technology</h2>
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
  // height: 400px;
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
  margin-top: 30px;
  margin-right: 30px;
  border-radius: 30px;
  color: white;
  background-color: rgb(38, 38, 230);
  border-color: blue;
}

img {
  width: 550px;
  height: 550px;
  margin-left: 470px;
  margin-top: 30px;
}

.title1 {
  color: white;
  font-weight: bold;
  margin-top: 150px;
}

.title2 {
  color: white;
  margin-top: 205px;
}
</style>

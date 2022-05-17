<template>
  <div class="section2">
    <div class="container-fluid">
      <div class="row">
        <div class="col-6">
          <img
            class="men-data"
            src="../assets/corporate-landing/images/men-data.png"
            alt="men-data"
          />
          <!-- <img
            class="nemoodar"
            src="../assets/corporate-landing/images/nemoodar.png"
            alt="men-data"
          /> -->
        </div>
        <div class="col-6">
          <h3 class="title1">Start your project</h3>
          <h1 class="title2">Grow Your Business</h1>
          <h2 class="title3">With Our Strategy</h2>
          <p class="vapour">
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
  name: "MainApp2",
};
</script>

<style lang="scss" scoped>
.section2 {
  width: 100%;
  background-color: #04174d;
}

.men-data {
  width: 300px;
  height: 300px;
  margin-top: 80px;
  margin-left: 100px;
  margin-bottom: 20px;
}

h3 {
  color: white;
  font-size: 10px;
  font-weight: bold;
  margin-top: 80px;
}

h1 {
  color: white;
  font-size: 30px;
  font-weight: bolder;
}

h2 {
  color: white;
  font-size: 30px;
}

.vapour {
  color: rgb(26, 26, 172);
  font-weight: bold;
}
// .nemoodar {
//   width: 250px;
//   height: 300px;
//   position: fixed;
//   top: 150px;
//   left: 50px;
//   bottom: 50px;
// }
</style>
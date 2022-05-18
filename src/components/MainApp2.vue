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
            the meridian sun strikes the upper surface.<br />
            while the lovely valley teams with vapour around.
          </p>
          <button class="try">Try now</button>
          <button class="explore">Explore more</button>
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
  margin-top: 40px;
  color: white;
  font-size: 30px;
  font-weight: bolder;
}

h2 {
  color: white;
  font-size: 30px;
}

.vapour {
  margin-top: 30px;
  color: rgb(26, 26, 172);
  font-weight: bold;
}

.try {
  width: 100px;
  height: 35px;
  background-color: #e44f6c;
  border: 1px solid #e44f6c;
  text-align: center;
  color: white;
  font-weight: 300;
  border-radius: 20px;
  margin-top: 25px;
  margin-right: 30px;
  margin-left: 30px;
}

.try:hover {
  background-color: rgb(61, 61, 190);
  border: 1px solid rgb(26, 26, 172);
}

.explore {
  width: 200px;
  height: 35px;
  background-color: rgb(61, 61, 190);
  border: 1px solid rgb(26, 26, 172);
  text-align: center;
  color: white;
  font-weight: 300;
  border-radius: 20px;
  margin-top: 25px;
  margin-bottom: 50px;
}

.explore:hover {
  background-color: #e44f6c;
  border: 1px solid #e44f6c;
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
<template>
  <div class="section4">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12">
          <h5 class="price">Price list</h5>
          <h2 class="pricing">Our Pricing</h2>
          <p>
            When, while the lovely valley teams with vapour around meand the
            meridian sun strikes <br />
            the upper surface.
          </p>
        </div>
      </div>
      <!-- <div class="row">
        <div class="col-4 designing"></div>
      </div> -->
    </div>
  </div>
</template>

<script>
export default {
  name: "MainApp4",
};
</script>

<style lang="scss" scoped>
.section4 {
  width: 100%;
  height: 500px;
  background-color: #04174d;
}

.price {
  color: rgb(240, 39, 39);
  text-align: center;
  font-size: 10px;
  margin-top: 30px;
}

.price:hover {
  font-size: 15px;
  font-weight: bold;
}

.pricing {
  color: white;
  text-align: center;
  margin-top: 10px;
  font-weight: bold;
}

p {
  color: white;
  text-align: center;
  font-size: 10px;
}

// .designing {
//   width: 100px;
//   background-color: white;
// }
</style>
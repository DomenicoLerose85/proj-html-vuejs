<template>
  <div class="section1">
    <div class="container">
      <div class="row">
        <div
          class="
            col-12
            d-flex
            flex-column
            justify-content-center
            align-items-center align-self-center
          "
        >
          <h3 class="red-h3">Our services</h3>
          <h2 class="what-we-do">What We Do</h2>
          <p class="lovely-valley">
            When, while the lovely valley teams with vapour around meand the
          </p>
        </div>
        <div class="col-12">
          <div class="card">
            <img
              class="group-247"
              src="../assets/corporate-landing/images/Group-247.png"
              alt="grp247"
            />
            <h3 class="data">Data Analyst</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainApp",
};
</script>

<style lang="scss">
.red-h3 {
  text-align: center;
  color: red;
  font-size: 10px;
  margin-top: 30px;
}

.what-we-do {
  margin-top: 5px;
}

.lovely-valley {
  font-size: 10px;
  color: grey;
}

.card {
  width: 100px;
}

.group-247 {
  width: 95px;
  height: 80px;
}

.data {
  text-align: center;
  padding-top: 20px;
  font-weight: 900;
  font-size: 12px;
}
</style>
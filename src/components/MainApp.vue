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
            <span
              >When, while the lovely valley teams with vapour around
              <br />meand the meridian sun strikes the upper</span
            >
          </div>
          <div class="card">
            <img
              class="group-538"
              src="../assets/corporate-landing/images/Group-538.png"
              alt="grp247"
            />
            <h3 class="data">SEO Optimizzation</h3>
            <span
              >When, while the lovely valley teams with vapour around
              <br />meand the meridian sun strikes the upper</span
            >
          </div>
          <div class="card">
            <img
              class="group-566"
              src="../assets/corporate-landing/images/Group-566.png"
              alt="grp247"
            />
            <h3 class="data">Security Data</h3>
            <span
              >When, while the lovely valley teams with vapour around
              <br />meand the meridian sun strikes the upper</span
            >
          </div>
          <div class="card">
            <img
              class="group-567"
              src="../assets/corporate-landing/images/Group-567.png"
              alt="grp247"
            />
            <h3 class="data">Branding Strategy</h3>
            <span
              >When, while the lovely valley teams with vapour around
              <br />meand the meridian sun strikes the upper</span
            >
          </div>
        </div>
        <div class="service_btn">
          <button class="services">View All Services</button>
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

<style lang="scss" scoped>
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
  width: 120px;
  border: none;
  display: inline-flex;
  margin-right: 20px;
  margin-left: 70px;
  margin-top: 40px;
}

.group-247 {
  width: 100px;
  height: 80px;
  padding-left: 10px;
}

.data {
  text-align: center;
  padding-top: 20px;
  font-weight: 900;
  font-size: 12px;
}

span {
  text-align: center;
  font-size: 10px;
  color: grey;
  padding-top: 20px;
  padding-bottom: 20px;
}

.group-538 {
  width: 100px;
  height: 80px;
  padding-left: 10px;
}

.group-566 {
  width: 100px;
  height: 80px;
  padding-left: 10px;
}

.group-567 {
  width: 100px;
  height: 80px;
  padding-left: 10px;
}

.services {
  margin-top: 100px;
  margin-left: 400px;
  margin-bottom: 100px;
  background-color: rgb(243, 166, 179);
  color: white;
  font-size: 15px;
  border-radius: 30px;
  border-color: pink;
}
</style>
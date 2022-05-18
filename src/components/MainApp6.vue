<template>
  <div class="section6">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12">
          <h5 class="testimonial">Testimonial</h5>
          <h2 class="people">What People Say</h2>
          <p>
            When, while the lovely valley teams with vapour around meand the
            meridian sun strikes <br />
            the upper surface.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-4">
          <div class="card-people">
            <img
              class="people1"
              src="../assets/corporate-landing/images/szabo-viktor-1266895-unsplash-1024x1024.png"
              alt="grp247"
            />
            <p>
              When, while the lovely valley teams with vapour around <br />meand
              the meridian sun strikes the upper impenetrable folliage of my
              trees, and but a thousand.
            </p>
            <h3 class="name">Mickel Anegl</h3>
            <h4 class="manager">Marketing Manager</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="card-people">
            <img
              class="people1"
              src="../assets/corporate-landing/images/philipe-cavalcante-539505-unsplash-1024x1024.png"
              alt="grp247"
            />
            <p>
              When, while the lovely valley teams with vapour around <br />meand
              the meridian sun strikes the upper impenetrable folliage of my
              trees, and but a thousand.
            </p>
            <h3 class="name">Mickel Anegl</h3>
            <h4 class="manager">Marketing Manager</h4>
          </div>
        </div>
        <div class="col-4">
          <div class="card-people">
            <img
              class="people1"
              src="../assets/corporate-landing/images/fabio-spinelli-695744-unsplash-1024x1024.png"
              alt="grp247"
            />
            <p>
              When, while the lovely valley teams with vapour around <br />meand
              the meridian sun strikes the upper impenetrable folliage of my
              trees, and but a thousand.
            </p>
            <h3 class="name">Mickel Anegl</h3>
            <h4 class="manager">Marketing Manager</h4>
          </div>
        </div>
      </div>
      <di class="container-fluid">
        <div class="row">
          <div class="col-2">
            <img
              class="golden"
              src="../assets/corporate-landing/images/client-1-1.png"
              alt="grp247"
            />
          </div>
          <div class="col-2">
            <img
              class="sweety"
              src="../assets/corporate-landing/images/clienty-2.png"
              alt="grp247"
            />
          </div>
          <div class="col-2">
            <img
              class="fast"
              src="../assets/corporate-landing/images/clienty-4.png"
              alt="grp247"
            />
          </div>
          <div class="col-2">
            <img
              class="jr"
              src="../assets/corporate-landing/images/clienty-3.png"
              alt="grp247"
            />
          </div>
        </div>
      </di>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainApp6",
};
</script>

<style lang="scss" scoped>
.card-people {
  margin-top: 100px;
  margin-bottom: 130px;
  margin-left: 50px;
}

.testimonial {
  color: rgb(235, 64, 64);
  text-align: center;
  font-size: 12px;
  margin-top: 30px;
}

.testimonial:hover {
  font-size: 18px;
  font-weight: bold;
}

.people {
  color: black;
  text-align: center;
  margin-top: 10px;
  font-weight: bold;
}

p {
  color: rgb(20, 20, 20);
  text-align: center;
  font-size: 15px;
}

.people1 {
  width: 120px;
  height: 120px;
  margin-left: 150px;
  margin-top: -30px;
  border: 4px solid rgb(240, 44, 77);
  border-radius: 50%;
}

.people1:hover {
  width: 150px;
  height: 150px;
}

p {
  text-align: center;
  margin-top: 40px;
}

.name {
  text-align: center;
  font-weight: bold;
  font-size: 20px;
  margin-top: 40px;
}

.manager {
  text-align: center;
  font-size: 15px;
  margin-top: 20px;
}

.golden,
.fast,
.jr {
  text-align: center;
  margin-left: 150px;
  margin-bottom: 60px;
}

.sweety {
  margin-left: 120px;
  margin-top: 5px;
  margin-bottom: 60px;
}
</style>
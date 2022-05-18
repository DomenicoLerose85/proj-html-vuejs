<template>
  <div class="section5">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12">
          <h5 class="blog">Blog</h5>
          <h2 class="posts">Latest Posts</h2>
          <p>
            When, while the lovely valley teams with vapour around meand the
            meridian sun strikes <br />
            the upper surface.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-6">
          <img
            class="headway"
            src="../assets/corporate-landing/images/headway-537308-unsplash-1380x703.jpg"
            alt="headway"
          />
          <h5 class="headway-date">April 21,2019 by Paul</h5>
          <h1 class="amazon">Amazon gets CCI nod to acquire 49% stake in</h1>
          <p class="amazon-p">
            When, while the lovely valley teams with vapour around me <br />
            and the meridian sun s..
          </p>
          <button class="read-more">Read More</button>
        </div>
        <div class="col-6">
          <div class="card1">
            <div class="card-body">
              <h6 class="card-date">April 21,2019 by Paul</h6>
              <h5 class="card-title">
                Clearing corporation get <br />
                SEBI nod to invest in <br />
                overnight funds
              </h5>
              <p class="card-text">
                When, while the lovely valley teams with vapour around me <br />
                and the meridian sun s..
              </p>
              <button class="read-more2">Read More</button>
            </div>
          </div>
          <div class="card2">
            <div class="card-body">
              <h6 class="card-date">April 21,2019 by Paul</h6>
              <h5 class="card-title">
                Shabnam Dhillion, wife of<br />
                RSSB Gurinder <br />
                Dhillion, passes away in London
              </h5>
              <p class="card-text">
                When, while the lovely valley teams with vapour around me <br />
                and the meridian sun s..
              </p>
              <button class="read-more3">Read More</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainApp5",
};
</script>

<style lang="scss" scoped>
.section5 {
  margin-bottom: 40px;
}

.blog {
  color: rgb(240, 39, 39);
  text-align: center;
  font-size: 12px;
  margin-top: 30px;
}

.posts {
  color: black;
  text-align: center;
  margin-top: 10px;
  font-weight: bold;
}

p {
  color: grey;
  font-weight: 800;
  text-align: center;
  font-size: 10px;
}

.headway {
  width: 400px;
  height: 200px;
  border-radius: 20px;
  margin-top: 30px;
}

.headway-date {
  color: white;
  font-size: 12px;
  margin-bottom: 10px;
  margin-top: -145px;
  margin-left: 10px;
}

.amazon {
  color: white;
  font-size: 14px;
  font-weight: bolder;
  margin-left: 10px;
}

.amazon-p {
  color: white;
  text-align: left;
  margin-left: 10px;
}

.read-more {
  background-color: white;
  color: black;
  position: absolute;
  left: 300px;
  border-radius: 30px;
  font-weight: 100;
}

.card1 {
  width: 250px;
  height: 300px;
  display: inline-block;
  background-color: #04174d;
  border-radius: 30px;
  margin-left: -210px;
  margin-top: 30px;
}

.card2 {
  width: 250px;
  height: 300px;
  display: inline-block;
  background-color: #04174d;
  border-radius: 30px;
  margin-left: 50px;
  margin-top: 30px;
}

.card-date {
  color: white;
  font-size: 12px;
  margin-left: 10px;
}

.card-title {
  color: white;
  font-weight: bold;
  margin-left: 10px;
}

.card-text {
  color: white;
  margin-left: 10px;
  font-weight: normal;
  text-align: left;
}

.read-more2 {
  background-color: white;
  color: black;
  position: absolute;
  left: 500px;
  border-radius: 30px;
  font-weight: 100;
  margin-top: 20px;
}

.read-more3 {
  background-color: white;
  color: black;
  position: absolute;
  left: 800px;
  border-radius: 30px;
  font-weight: 100;
  margin-top: 20px;
}
</style>
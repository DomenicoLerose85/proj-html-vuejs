<template>
  <div class="section3">
    <div class="container-fluid">
      <div class="row">
        <div class="col-6">
          <h4 class="portfolio">Portfolio</h4>
          <h2 class="latest-work">latest work</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-4">
          <img
            class="books"
            src="../assets/corporate-landing/images/8wa60okr-1-790x576.jpg"
            alt=""
          />
          <h2 class="basket">Basket of flower on table</h2>
        </div>
        <div class="col-4">
          <img
            class="phones"
            src="../assets/corporate-landing/images/84316050-0af0-49db-a53a-241d47ddad0e-2-790x576.jpg"
            alt=""
          />
          <h2 class="basket">Purinky products</h2>
        </div>
        <div class="col-4">
          <img
            class="book"
            src="../assets/corporate-landing/images/a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg"
            alt=""
          />
          <h2 class="basket">Satisfy poster</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainApp3",
};
</script>

<style lang="scss" scoped>
.portfolio {
  color: red;
  font-size: 10px;
  margin-top: 50px;
  margin-left: 20px;
}

.latest-work {
  font-weight: 500;
  margin-left: 20px;
}

.basket {
  font-weight: 700;
  font-size: 15px;
  margin-left: 45px;
  margin-bottom: 100px;
  margin-top: -80px;
}

.books,
.phones,
.book {
  margin-left: 45px;
  margin-top: 50px;
  margin-bottom: 100px;
  width: 300px;
  height: 250px;
  border-radius: 20px;
}

.books:hover {
  width: 350px;
  height: 300px;
}
.phones:hover {
  width: 350px;
  height: 300px;
}
.book:hover {
  width: 350px;
  height: 300px;
}
</style>
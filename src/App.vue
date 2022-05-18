<template>
  <div id="app">
    <header-app />
    <main-app />
    <main-app-2 />
    <main-app-3 />
    <main-app-4 />
    <main-app-5 />
    <main-app-6 />
    <footer-app />
  </div>
</template>

<script>
import HeaderApp from "./components/HeaderApp.vue";
import MainApp from "./components/MainApp.vue";
import MainApp2 from "./components/MainApp2.vue";
import MainApp3 from "./components/MainApp3.vue";
import MainApp4 from "./components/MainApp4.vue";
import MainApp5 from "./components/MainApp5.vue";
import MainApp6 from "./components/MainApp6.vue";
import FooterApp from "./components/FooterApp.vue";

export default {
  name: "App",
  components: {
    HeaderApp,
    MainApp,
    MainApp2,
    MainApp3,
    MainApp4,
    MainApp5,
    MainApp6,
    FooterApp,
  },
};
</script>

<style lang="scss">
@import "./assets/style/general.scss";
</style>

<template>
  <div id="app">
    <header-app />
    <main-app />
    <main-app-2 />
    <footer-app />
  </div>
</template>

<script>
import HeaderApp from "./components/HeaderApp.vue";
import MainApp from "./components/MainApp.vue";
import MainApp2 from "./components/MainApp2.vue";
import FooterApp from "./components/FooterApp.vue";

export default {
  name: "App",
  components: {
    HeaderApp,
    MainApp,
    MainApp2,
    FooterApp,
  },
};
</script>

<style lang="scss">
@import "./assets/style/general.scss";
</style>

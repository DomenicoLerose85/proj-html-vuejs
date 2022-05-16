<template>
  <div id="app">
    <header-app />
  </div>
</template>

<script>
import headerApp from "./components/headerApp.vue";

export default {
  name: "App",
  components: {
    headerApp,
  },
};
</script>

<style lang="scss">
@import "./assets/style/general.scss";
</style>

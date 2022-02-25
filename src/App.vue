<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Calcul msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import Calcul from "./components/Calcul.vue";

export default {
  name: "App",
  components: {
    Calcul,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

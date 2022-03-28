<template>
  <div id="app">
    <the-header title="RememberMe"></the-header>
    <the-resource></the-resource>
  </div>
</template>

<script>
import TheHeader from "./components/layouts/TheHeader.vue";
import TheResource from "./components/learning-resources/TheResource.vue";

export default {
  name: 'App',
  components: {
    TheHeader,
    TheResource,
  },

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,500;0,700;0,900;1,300;1,500;1,700;1,900&display=swap');
* {
  box-sizing: border-box;
}
html, body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
}
/*#app {*/
/*  font-family: Avenir, Helvetica, Arial, sans-serif;*/
/*  -webkit-font-smoothing: antialiased;*/
/*  -moz-osx-font-smoothing: grayscale;*/
/*  text-align: center;*/
/*  color: #2c3e50;*/
/*  margin-top: 60px;*/
/*}*/
</style>

<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <totalhour />
  </div>
</template>

<script>

import totalhour from './components/totalhour.vue'
export default {
  name: 'App',
  components: {
    totalhour
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

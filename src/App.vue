<template>
  <div id="app">
      <Home/>
  </div>
</template>

<script>

import Home from './views/Home.vue';

export default {
  name: 'App',
  components: {
    Home
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
  background: rgba(97, 10, 97, 0.747);
  width: 60vw;
  margin:0 auto;
  padding: 5vw;
  padding-bottom: 10vw;
  border-radius:2vw ;
}
</style>

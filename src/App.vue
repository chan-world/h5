<template>
  <div id="app">
    <WholeProject />
  </div>
</template>

<script>
import WholeProject from './components/WholeProject.vue'

export default {
  name: 'App',
  components: {
    WholeProject
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

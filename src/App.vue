<template>
  <div id="app">
    <loancalculator/>
  </div>
</template>

<script>
import loancalculator from './components/loancalculator.vue'

export default {
  name: 'App',
  components: {
    loancalculator
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

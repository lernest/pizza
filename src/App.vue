<template>
  <div id="app">
    <Pizza />
  </div>
</template>

<script>
import Pizza from './components/Pizza.vue'

export default {
  name: 'App',
  components: {
    Pizza,
  },
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

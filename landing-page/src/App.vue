<template>
  <div id="app">
    <NavBar />
    <JumboTron />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    JumboTron,
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
}
</style>

<template>
  <div id="app">
    <NavBar />
    <JumboTron />
    <CTA />
    <ContentCards />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import JumboTron from './components/JumboTron.vue'
import CTA from './components/CTA.vue'
import ContentCards from './components/ContentCards.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    JumboTron,
    CTA,
    ContentCards,
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

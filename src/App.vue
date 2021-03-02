<template>
  <div id="app">
    <CardsPage/>
  </div>
</template>

<script>
import CardsPage from './components/CardsPage.vue'

export default {
  components: {
    CardsPage
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

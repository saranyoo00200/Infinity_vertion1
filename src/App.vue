<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/download.jpg">
    <game/>
  </div>
</template>

<script>
import game from './components/game.vue'

export default {
  name: 'App',
  components: {
    game,
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

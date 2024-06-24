<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div class="bg-red-500 text-3xl font-bold text-green-400">TEST</div>
  <TheHome></TheHome>
</template>

<script>
import TheHome from './components/TheHome.vue'

export default {
  name: 'App',
  components: {
    TheHome
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

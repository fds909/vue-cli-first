<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleComp></TitleComp>
  </div>
</template>

<script>
import TitleComp from './components/TitleComp.vue'

export default {
  name: 'App',
  components: {
    TitleComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

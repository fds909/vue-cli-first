<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleComp></TitleComp>
    <HeroComp></HeroComp>
  </div>
</template>

<script>
import TitleComp from './components/TitleComp.vue'
import HeroComp from './components/HeroComp.vue'

export default {
  name: 'App',
  components: {
    TitleComp,
    HeroComp
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

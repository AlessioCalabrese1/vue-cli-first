<template>
  <div id="app">
    <FirstTitle/>
    <HeroJumbotron />
  </div>
</template>

<script>
import HeroJumbotron from './components/HeroJumbotron.vue'
import FirstTitle from './components/FirstTitle.vue'

export default {
  name: 'App',
  components: {
    HeroJumbotron,
    FirstTitle
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

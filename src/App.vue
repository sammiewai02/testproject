<template>
  <div id="app">
    <home></home>
    <contact></contact>
    <bottom></bottom>
  </div>
</template>

<script>
import Home from './components/Home'
import Contact from './components/Contact'
import Bottom from './components/Bottom'

export default {
  name: 'app',
  components: {
    Home,
    Contact,
    Bottom
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

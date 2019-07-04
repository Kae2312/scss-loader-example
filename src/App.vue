<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Kikou />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Kikou from './components/Kikou.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Kikou
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $primary;
  margin-top: 60px;
}
</style>

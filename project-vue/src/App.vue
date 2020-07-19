<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MiComponente/>
    <Directivas/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/MiComponente.vue'
import Directivas from './components/Directivas.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente,
    Directivas
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

@import './assets/css/styles.css';
</style>

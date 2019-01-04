<template>
  <div id="app">
    <Header></Header>
    <RestoInfo></RestoInfo>
    <Tableau></Tableau>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header/Header.vue'
import RestoInfo from './components/RestoInfoBar/RestoInfo.vue'
import Tableau from './components/Tableau/Tableau.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Header,
    RestoInfo,
    Tableau
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

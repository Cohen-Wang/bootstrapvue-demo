<template>
  <div id="app">

    <Navbar></Navbar>
    <Cards></Cards>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import Cards from './components/Cards.vue'


export default {
  name: 'app',
  components: {
    //HelloWorld,
    Navbar,
    Cards
  }
}
</script>

<style>
/*#app {*/
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
/*}*/
</style>

<template>
  <div id="app">
    <HelloWorld msg="WELCOME TO INTERNSHIP PAGE"/>
    <comp></comp>
    
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Comp from './components/comp.vue'



export default {
  name: 'App',
  components: {
    HelloWorld,
    Comp,
  
   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-color: darkgreen;
  margin-top: 60px;
}
</style>

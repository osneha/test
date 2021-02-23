<template>
  <div id="app">
    <HelloWorld msg="Welcome to TEST APP by Sneha"/>
    <comp> </comp>
    <header></header>
    <footer></footer>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Component from './components/Component'
import Header from './components/header.vue'
import Footer from './components/footer.vue'




export default {
  name: 'App',
  components: {
    HelloWorld,
    Component,
    Header,
    Footer
   
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

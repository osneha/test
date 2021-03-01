<template>
  <div id="app">
    <HelloWorld msg="WELCOME TO INTERNSHIP PAGE"/>
    <comp></comp>
    <v-app>
      <v-footer>
        <Footer />
      </v-footer>
      <f></f>

    
    </v-app>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Comp from './components/comp.vue'
import { mdbFooter, mdbContainer, mdbRow, mdbCol } from 'f.vue';


export default {
  name: 'App',
  components: {
    HelloWorld,
    Comp, mdbFooter,
      mdbContainer,
      mdbRow,
      mdbCol
  
   
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
  background-color: #006747;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <HelloWorld msg="WELCOME TO INTERNSHIP PAGE"/>
    <v-app>
      <Landing />
      <Footer />
    </v-app>
  </div>
</template>
<script>
import Landing from './components/landing.vue'
import Footer from './components/f.vue'
export default {
  name: 'App',
  components: {
     Landing,
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
  color: white;
  background-color: #006747;
  margin-top: 60px;
}
</style>

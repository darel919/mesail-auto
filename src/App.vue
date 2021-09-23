<template>
  <div id="app">
    <Navbar/>
    <router-view/>
  </div>
</template>
<script>
import Navbar from '@/components/navbar.vue'

export default {
  components: {
    Navbar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat');

#app {
  font-family: Montserrat;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  
}
body, html, #app {
  scroll-behavior: smooth;
  margin:0;
  padding:0;
  background:rgb(20, 20, 20);
}
a, a :visited, a:focus, html, body, #app {
    text-decoration: none;
    color:inherit;
}
</style>

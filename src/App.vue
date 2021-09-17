<template>
  <div id="app">
    <!-- <div id="nav"> -->
      <!-- <router-link to="/">Home</router-link> | -->
      <!-- <router-link to="/about">About</router-link> -->
    <!-- </div> -->
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
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

#app {
  font-family: Montserrat;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* overflow: hidden; */
  color: white;
  /* font-weight: lighter; */
}
body, html, #app {
  margin:0;
  padding:0;
  background:rgb(20, 20, 20);
}
a, a :visited, a:focus, html, body, #app {
    text-decoration: none;
    color:inherit;
}
/* #nav {
  padding: 30px;
} */

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

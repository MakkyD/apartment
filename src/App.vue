<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
      
     
      
    </div>
    
    <router-view/>
    
  </div>
</template>


<script>

import Footer from "./components/Footer.vue";
export default{
  components: {
    // "app-header": Header,
    // "app-footer": Footer
  }
}
</script>


<style>


#app {
  /* font-family: 'EB Garamond', serif; */
  font-family: 'EB Garamond', serif;
font-family: 'Overpass', sans-serif;
/* font-family: 'Overpass', sans-serif; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  /* text-align: center; */
  /* color: #2c3e50; */
}

#nav {
  /* padding: 30px; */
 
}

#nav a {
 
  /* color:red; */
}

/* #nav a.router-link-exact-active {
  color: #42b983;
} */
.footer{
  background-color: rgb(8, 27, 47);
  color:white;
}
</style>

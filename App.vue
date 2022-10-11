<template>
  
<header>
  <Navbar msg="fdfds"/>
</header>


  <body>

    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    
  </body>



  <footer>

  </footer>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>

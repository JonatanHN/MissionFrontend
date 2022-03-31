<template>
  <NavBar/>
  <router-view/>
  <Footer/>
</template>



<script>
// @ is an alias to /src
import Home from '@/views/HomeView.vue'
import Pastelero from '@/views/PasteleroView.vue'
import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Home,
    Pastelero,
    NavBar,
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
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

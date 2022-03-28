<template>
  <nav>
    <router-link to="/">Inicio</router-link> |
    <router-link to="/pastelero">Pastelero</router-link>
</nav>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar
  }
}
</script>
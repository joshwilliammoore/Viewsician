<template>
  <Navbar msg="d v" />
  <img alt="Vue logo" src="./assets/logo.png" />
  <Index msg="Hello Vue 3.0 + Vite" />
</template>

<script>
import Index from './components/Index.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Index,
    Navbar,
  }
}
</script>

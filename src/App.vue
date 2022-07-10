<script lang="ts">
// import { RouterLink, RouterView } from 'vue-router'
import MainNav from '@/components/mainNav/MainNav.vue'

export default {
  name: 'App', 
  components: {
    MainNav
  }
}
</script>

<template>  
  <header>
    <main-nav />
  </header>
 
  <RouterView />
</template>

<style>
@import '@/assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  font-weight: normal;
}
</style>

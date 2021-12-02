<script setup lang="ts">
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup

import Header from './components/Header.vue'
import Results from './components/Results.vue'
import Footer from './components/Footer.vue'

</script>

<template>
  <Header />
  <Results />
  <Footer />
</template>

<style>
body {
  background: #2c3e50;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
</style>

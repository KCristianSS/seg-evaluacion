<script setup>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div>
    <Navbar />
    <router-view />
    <Footer />
  </div>
</template>

<style scoped>
/* Estilos opcionales */
</style>

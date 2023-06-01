<script setup>
import { RouterLink, RouterView } from 'vue-router'
import MainPage from './views/MainPage.vue';
import Navbar from './components/Navbar.vue'
</script>

<template>
  <header>
   <Navbar/>
     
  </header>
  <RouterView />
</template>
<style src="./assets/main.css"></style>

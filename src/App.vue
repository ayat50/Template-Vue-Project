<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>
  
<template>
  <main class="flex-shrink-0">
    <nav>
    </nav>

    <Navbar></Navbar>
    <RouterView/>
    <Footer></Footer>

  </main>
</template>

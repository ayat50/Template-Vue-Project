<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import Test from './components/Test.vue'
</script>
  
<template>
  <main class="flex-shrink-0">
    <nav>
    </nav>
<!-- 
    <Test name="nazmul" mobile="01812454558"></Test>
    <Test name="nazmul" mobile="01812454558"></Test>
    <Test name="nazmul" mobile="01812454558"></Test> -->

    <Navbar></Navbar>
    <RouterView/>
    <Footer></Footer>

  </main>
</template>

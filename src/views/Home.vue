<template>
  <div class="home container">
  <Navbar></Navbar>
      <Hero/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
//import Navbar from '@/components/Navbar.vue'
import Hero from '@/components/Hero.vue'
import Products from "@/sections/Products.vue"

export default {
  name: 'Home',
  components: {
    Hero,
    Products
    //HelloWorld
    //Navbar
  }
}
</script>

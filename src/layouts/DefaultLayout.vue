<template>
  <div>
    <Navbar />
    <main>
      <slot />
    </main>
    <Footer />
  </div>
</template>

<script setup lang="ts">
import Footer from '../components/Footer.vue';
import Navbar from '../components/Navbar.vue';
</script>

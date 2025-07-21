<template>
  <div class="homepage-wrapper grid">
    <Header />
    <Hero />

    <main class="main_content">
      <NuxtPage />
    </main>

    <Footer />
  </div>
</template>

<script setup>
import Header from '~/components/layout/Header.vue'
import Footer from '~/components/layout/Footer.vue'
import Hero from '~/components/pages/Hero.vue'
</script>

<style scoped>


</style>

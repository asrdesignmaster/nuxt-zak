<template>
  <div>
    <div class="">
      <Header />
    </div>
    <main class="page-content">
          <NuxtPage />
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Header from '~/components/layout/Header.vue'
import Footer from '~/components/layout/Footer.vue'
</script>

<style scoped>
.header {
  border-bottom: 1px solid #eaeaea;
}

</style>

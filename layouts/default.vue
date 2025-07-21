<template>
  <div>
    <div class="">
      <Header />
    </div>
    <main class="page-content">
      <div class="container">
        <div class="main_content_wrapper">
          <NuxtPage />
        </div>
      </div>
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
.page-content {
  padding-top: 32px;
}
</style>

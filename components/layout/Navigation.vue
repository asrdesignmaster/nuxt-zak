<template>
    <nav class="nav  md:flex hidden">
      <Nav />
      <NuxtLink to="tel:1234567890">
        <span class="sr-only">Call us</span>
        <Icon name="material-symbols:call" class="text-gray-800 text-3xl" />
      </NuxtLink>
      <NuxtLink to="mailto:test@test.com">
        <span class="sr-only">Email us</span>
        <Icon name="material-symbols:mail-outline-rounded" class="text-gray-800 text-3xl" />
      </NuxtLink>
    </nav>
</template>
<script setup>
import Nav from '~/components/layout/Nav.vue'
</script>
<style scoped>
.nav {
  gap: 15px;
  padding: 10px;
}
</style>

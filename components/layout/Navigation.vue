<template>
    <nav class="nav  md:flex hidden">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about-us">About <span class="sr-only">about Paradise Leafing Art</span></NuxtLink>
      <NuxtLink to="/gallery">Gallery</NuxtLink>
      <NuxtLink to="/contact">Contact</NuxtLink>
      <NuxtLink to="tel:1234567890">
        <span class="sr-only">Call us</span>
        <svg class="text-gray-800 text-2xl" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><!-- Icon from Material Symbols by Google - https://github.com/google/material-design-icons/blob/master/LICENSE --><path fill="currentColor" d="M19.95 21q-3.125 0-6.187-1.35T8.2 15.8t-3.85-5.55T3 4.05V3h5.9l.925 5.025l-2.85 2.875q.55.975 1.225 1.85t1.45 1.625q.725.725 1.588 1.388T13.1 17l2.9-2.9l5 1.025V21z"/></svg>
      </NuxtLink>
      <NuxtLink to="mailto:test@test.com">
        <span class="sr-only">Email us</span>
        <svg class="text-gray-800 text-xl " xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><!-- Icon from Material Symbols by Google - https://github.com/google/material-design-icons/blob/master/LICENSE --><path fill="currentColor" d="M2 20V4h20v16zm10-7L4 8v10h16V8zm0-2l8-5H4zM4 8V6v12z"/></svg>
      </NuxtLink>
    </nav>
</template>
<script setup>
</script>
<style scoped>
.nav {
  gap: 15px;
  padding: 10px;
}
</style>

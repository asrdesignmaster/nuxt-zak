<template>
  <footer class="footer">
    <p>&copy; 2025 {{ config.siteName }}. All rights reserved.</p>
  </footer>
</template>

<script setup>
const config = useAppConfig()
</script>
<style scoped>
.footer {
  padding: 20px;
  background-color: #000;
  color: white;
  text-align: center;
}
</style>

<template>
  <header class="header backdrop-blur-xs">

      <div class="container">
        <div class="header_content">
          
          <div class="logo">
            <NuxtImg 
              src="/images/zak-logistics-logo.svg" 
              alt="Zak Logistcis Logo" 
              width="330" 
              height="80" 
              class="w-40 lg:w-full h-auto lg:h-20 "
              />
          </div>
          <Navigation />
          <div class="toggle_btn lg:hidden">
            <Icon name="material-symbols:menu" size="24" />
          </div>
        </div>
      </div>
  </header>
</template>

<script setup>
import Navigation from '~/components/layout/Navigation.vue'

</script>
<style scoped>
.header .logo {
  width: 330px;
  height: auto;
}
.header_content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>

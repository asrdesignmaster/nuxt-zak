<template>
  <header class="header backdrop-blur-xs min-h-12 lg:min-h-24 py-4 relative z-50  h-fit lg:h-auto">

    <div class="container">
      <div class="header_content">

        <div class="logo">
          <NuxtImg src="/images/zak-logistics-logo.svg" alt="Zak Logistcis Logo" width="330" height="80"
            class="w-40 lg:w-full h-auto lg:h-20 " />
        </div>
        <div class="hidden lg:inline-block">
          <Navigation />
        </div>
        <!-- Toggle Button -->
        <div class="toggle_btn lg:hidden">
          <Icon name="material-symbols:menu" size="24" id="menu-button" @click="toggleMenu" />
        </div>

        <!-- Mobile Menu -->
        <div v-show="isMenuOpen" id="mobile-menu"
          class="mt-5 space-y-4 absolute top-10 left-0 right-0 bottom-0 z-50 h-fit">
          <!-- 👇 Listen for the emitted event from Navigation -->
          <Navigation @menu-item-clicked="closeMenu" />
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import Navigation from '~/components/layout/Navigation.vue'


const isMenuOpen = ref(false);

function toggleMenu() {
  isMenuOpen.value = !isMenuOpen.value;
}

function closeMenu() {
  isMenuOpen.value = false;
}

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

#mobile-menu {
  transition: opacity 0.3s;
  box-shadow: 0px 8px 10px #00000035;
  background-color: #fff;

  nav {
    display: flex;
    flex-direction: column;
    background-color: white;
    margin-left: 10px !important;


  }
}

@media (min-width:768px) {
  #mobile-menu {
    display: block;
  }
}
</style>

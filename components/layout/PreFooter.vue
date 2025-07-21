<template>
    
  <div class="pre_footer | py-20">
    <div class="container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="">
          <NuxtImg src="/images/zak-logistics-logo-white.svg" alt="Logo" class="w-64 mb-4" />
          <p class="text-white mt-2">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
erat, sed diam voluptua.</p>
        </div>
        <div class="text-white mx-auto">
          <h3 class="mb-4 text-xl">Useful Links</h3>
          <nav class="footer_nav">
            <Nav />
          </nav>
        </div>
        <div class="text-white">
          <div class="flex items-center gap-4">
            <a href="" target="_blank" rel="noopener noreferrer">
              <Icon name="mdi:facebook" class="text-4xl" />
            </a>
            <a href="" target="_blank" rel="noopener noreferrer">
              <Icon name="ri:linkedin-box-fill" class="text-4xl" />
            </a>
            <a href="" target="_blank" rel="noopener noreferrer">
              <Icon name="ic:outline-whatsapp" class="text-4xl" />
            </a>
          </div>
          <div class="mt-4">
            <p class="mt-0.5 flex items-center gap-3 mb-3">
              <span>
                <Icon name="ic:outline-whatsapp" class="text-3xl" />
              </span> 
              +91 2222223333</p>
              <p class="mt-0.5 flex items-center gap-3">
                <span>
                <Icon name="material-symbols:mail-outline-rounded" class="text-3xl" />
              </span>
              support@zaklogistics.com</p>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script setup>
import Nav from '~/components/layout/Nav.vue'
</script>

<style>
.footer_nav{
  display: flex;
  flex-direction: column;
  gap: 10px;
}
</style>
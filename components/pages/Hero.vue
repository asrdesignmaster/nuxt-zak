<template>
    <section class="hero | relative brightness-[.9] overflow-hidden">
      <div class="gr_curtain"></div>
      <Icon name="hugeicons:safe-delivery-02" class="delivery_icon | absolute left-1/12 z-10 text-9xl text-white opacity-30" />
      <h1 class="text-white text-8xl md:text-9xl lg:text-[200px] leading-24 md:leading-34 lg:leading-60 | font-bold text-shadow-gray-800 text-shadow-lg/30 opacity-25">Logistics</h1>
      <p class="text-xl md:text-3xl lg:text-4xl my-5 uppercase font-bold relative z-20 ">Safe & Reliable Cargo Solutions</p>
    <Button link="/about-us" size="md" class="relative z-20 ">Read more<span class="sr-only">About Paradise {{ config.siteName }}</span></Button>

    </section>
</template>

<script setup>
import Button from '~/components/common/LinkButton.vue'
const config = useAppConfig()
</script>
<style scoped>

.hero {
  background: url('/images/zak-bg.webp') no-repeat center center;
  background-attachment: fixed;
  color: white;
  padding: 60px 20px;
  text-align: center;
  height: 90vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 165px;

  .delivery_icon{
     position: absolute; 
     bottom: 0; 
     animation: animate-icon 12s ease-in-out; 
  }
}
@keyframes animate-icon { 0% { transform: translateY(-710%); } 
100% { transform: translateY(0%); } }

.gr_curtain {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(180deg, #0E2D43 0%, rgba(216, 216, 216, 0) 100%);
  mix-blend-mode: multiply;
  opacity: 0.5;
}
@media (max-width: 768px) {
  .hero {
    /* background-position: center right; */
  }
  
}
</style>
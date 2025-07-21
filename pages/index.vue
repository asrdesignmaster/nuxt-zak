<template>
  <section class="about_us">
    <div class="container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4 mt-10 py-20 relative lg:h-[720px]">
        <div class="relative ">
          <NuxtImg src="/images/about.webp" width="400" height="auto"
            class="rounded-4xl shadow-lg relative top-0 left-0 md:ablolute" alt="Hero Image" />
          <NuxtImg src="/images/about-2.webp" width="400" height="auto"
            class="rounded-4xl shadow-lg  absolute top-48 left-48 z-10 hidden md:block lg:block" alt="Hero Image" />
        </div>
        <div class="about_us | text-left h-fit lg:sticky relative top-4">
          <h3 class="mb-2 uppercase text-gray-700">About us</h3>
          <h2>Reliable & Express Logistic & Transport Solutions That Saves Your Time!</h2>
          <p class="text-xl text-gray-500">ZAK Logistics is an innovative and energetic shipping / Freight forwarding
            company.  which has rapidly grown in it's range of service turnover and geographic coverage establishing
            itself as a leading forwarder in India.</p>
        </div>
      </div>

    </div>
  </section>

  <section class="expertise | bg-black text-white text-center relative py-40 overflow-hidden">
    <div class="plane">
      <NuxtImg src="images/plane-vector.svg" class="absolute -top-30 -right-40 -rotate-45 w-[650px]" />
    </div>
    <h2 class="text-white font-light">Our Expertise</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 mt-10">
      <div class="card goods">
        <div class="card_curtain"></div>
        <div class="card_content">
          All Types of DG goods &Auto Parts
        </div>
      </div>
      <div class="card ceramics">
        <div class="card_curtain"></div>
        <div class="card_content">
          Ceramics & Vitrified Tiles, Sanitary Ware & Bathroom Fittings
        </div>

      </div>
      <div class="card furniture">
        <div class="card_curtain"></div>
        <div class="card_content">
          Building Glass, Doors, Furniture & Building materials.
        </div>

      </div>
      <div class="card electronics">
        <div class="card_curtain"></div>
        <div class="card_content">
          Consumer products, Electronic & Electrical Commodities
        </div>

      </div>
      <div class="card glass">
        <div class="card_curtain"></div>
        <div class="card_content">
          Industrial Electronic components & Glass ware products
        </div>

      </div>
    </div>
  </section>

  <section class="why_us">
    <div class="container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4 mt-10 py-20 relative">
        <div class="relative lg:sticky top-4 h-fit">
          <h3 class="mb-2 uppercase text-gray-700 text-center lg:text-left">Why choose us</h3>
          <h2 class="text-5xl leading-16 text-center lg:text-left">Today’s Fast-Paced World, <br /> Efficient Logistics.</h2>
        </div>
        <div class="grid grid-cols-1 text-center sm:mt-8 sm:grid-cols-2  md:grid-cols-2 gap-4">
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="basil:headset-solid" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Quick Support</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
            </div>
            <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="lucide:satellite-dish" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Real-Time Tracking</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
            </div>
            <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="material-symbols:delivery-truck-speed-outline-rounded" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Quick Support</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
            </div>
            <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
              <Icon name="ic:outline-payment" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Real-Time Tracking</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="our_work py-40 relative">
    <div class="curtain"></div>
    <div class="left_plane"><img src="/images/plane-vector.svg" alt="plane" /></div>
    <div class="right_plane"><img src="/images/plane-vector.svg" alt="plane" /></div>
    <div class="relative z-10">
      <h3 class="text-white text-center z-50 text-4xl mb-8">Our Work</h3>
      <div class="text-center text-white flex justify-center items-center gap-10 flex-wrap">
        <div class="">
          <h2 class="text-white text-7xl">83+</h2>
          <p class="text-2xl uppercase">Clients Worldwide</p>
        </div>
        <div class="">
          <h2 class="text-white text-7xl">36+</h2>
          <p class="text-2xl uppercase">Countries Covered</p>
        </div>
        <div class="">
          <h2 class="text-white text-7xl">1550+</h2>
          <p class="text-2xl uppercase">Delivered Packages</p>
        </div>
      </div>
    </div>

  </section>

  <section class="work_process py-40 ">
    <div class="container">
      <h3 class="uppercase text-gray-700 mb-8 text-center">Work Process</h3>
      <h2 class="text-center text-5xl">Today’s Fast-Paced World's Efficient Logistics.</h2>
      <div class="relative flex flex-col md:flex-row items-center justify-between gap-12 md:gap-6">
        <!-- Wavy Dashed Line (SVG) -->
           <img src="/images/wave.svg" alt="Wavy Dashed Line"class="hidden md:block absolute left-0 right-0 top-1/3 transform -translate-y-1/2 z-0" />
           
        <!-- Step 1 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <img src="/images/receive_package.webp" alt="Step 1"
              class="w-60 h-60 rounded-full object-cover border-4 border-white shadow-md" />
            <span
              class="absolute top-4 right-4 bg-yellow-400 w-10 h-10 rounded-full flex items-center justify-center font-bold text-black">01</span>
          </div>
          <h3 class="text-xl font-semibold mt-6">Step 1: Receive Package</h3>
          <p class="text-gray-600 text-lg mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit. Mauris nullam
            the as integer.</p>
        </div>

        <!-- Step 2 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <img src="/images/transport.webp" alt="Step 2"
              class="w-60 h-60 rounded-full object-cover border-4 border-white shadow-md" />
            <span
              class="absolute top-4 right-4 bg-yellow-400 w-10 h-10 rounded-full flex items-center justify-center font-bold text-black">02</span>
          </div>
          <h3 class="text-xl font-semibold mt-6">Step 2: Transport Packages</h3>
          <p class="text-gray-600 text-lg mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit. Mauris nullam
            the as integer.</p>
        </div>

        <!-- Step 3 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <img src="/images/deliver.webp" alt="Step 3"
              class="w-60 h-60 rounded-full object-cover border-4 border-white shadow-md" />
            <span
              class="absolute top-4 right-4 bg-yellow-400 w-10 h-10 rounded-full flex items-center justify-center font-bold text-black">03</span>
          </div>
          <h3 class="text-xl font-semibold mt-6">Step 3: Deliver Packages</h3>
          <p class="text-gray-600 text-lg mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit. Mauris nullam
            the as integer.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="pre_footer | bg-gray-900">
    <PreFooter />
  </section>


</template>

<script setup>
import Button from '~/components/common/LinkButton.vue'
import PreFooter from '~/components/layout/PreFooter.vue'

const config = useAppConfig()

definePageMeta({
  layout: 'homepage'
})

useHead({
  title: 'Home | ' + config.siteName,
  meta: [
    {
      name: 'description',
      content: 'Gold and silver leafing services for furniture, religious places, and interior decor across India.'
    }
  ]
})

</script>
<style scoped>
.expertise {
  .card {
    position: relative;
    min-height: 530px;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .card_content {
    position: absolute;
    bottom: 20px;
    font-size: 26px;
    font-weight: bold;
    line-height: 36px;
    text-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
    padding-inline: 16px;
  }

  .card_curtain {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    mix-blend-mode: multiply;
    background: linear-gradient(0deg, #051C29 0%, rgba(216, 216, 216, 0) 58%);
    transition: opacity 0.3s ease;
  }

  .goods {
    background: url('/images/goods.webp');
  }

  .ceramics {
    background: url('/images/ceramics.webp');
  }

  .furniture {
    background: url('/images/furniture.webp');
  }

  .electronics {
    background: url('/images/electronics.webp');
  }

  .glass {
    background: url('/images/glass.webp');
  }

}

.our_work {
  background: url('/images/our_work.webp');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.our_work {

  .left_plane,
  .right_plane {
    position: absolute;
    width: 200px;
    height: 200px;
    z-index: 2;
    top: 50%;
    transform: translateY(-50%);
  }

  .right_plane {
    top: 50%;
    right: 25px;

  }
}

@media (max-width: 768px) {
  .expertise {
    .card {
      min-height: 350px;
    }
  }

  .our_work {

    .left_plane {
      left: -88px;
    }

    .right_plane {
      right: -88px;
    }
  }
}
</style>

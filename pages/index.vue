<template>
  <section class="about_us">
    <div class="container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4 mt-10 py-20 relative lg:h-[720px]">
        <div class="relative ">
          <NuxtImg src="/images/about.webp" width="400" height="auto" loading="lazy"
            class="rounded-4xl shadow-lg relative top-0 left-0 md:ablolute" alt="Hero Image" />
          <NuxtImg src="/images/about-2.webp" width="400" height="auto" loading="lazy"
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

  <section class="expertise | bg-black text-white text-center relative py-40 overflow-hidden" loading="lazy">
    <div class="plane">
      <NuxtImg src="images/plane-vector.svg" class="absolute -top-30 -right-40 -rotate-45 w-[650px]" loading="lazy" />
    </div>
    <h2 class="text-white font-light">Our Expertise</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 mt-10">
      <div class="card goods | ">
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

  <section class="why_us" loading="lazy">
    <div class="container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4 mt-10 py-20 relative">
        <div class="relative lg:sticky top-4 h-fit">
          <h3 class="mb-2 uppercase text-gray-700 text-center lg:text-left">Why choose us</h3>
          <h2 class="text-5xl leading-16 text-center lg:text-left">Today’s Fast-Paced World, <br /> Efficient Logistics.
          </h2>
        </div>
        <div class="grid grid-cols-1 text-center sm:mt-8 sm:grid-cols-2  md:grid-cols-2 gap-4">
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="basil:headset-solid" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Quick Support</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled.</p>
          </div>
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="lucide:satellite-dish" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Real-Time Tracking</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
          </div>
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="material-symbols:delivery-truck-speed-outline-rounded" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Fast & Efficient Delivery</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled.</p>
          </div>
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <Icon name="ic:outline-payment" class="text-gray-700 text-6xl mx-auto" />
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Easy Payment Methods</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <OurWork />

  <WorkProcess />

  <section class="contact_now | py-20 bg-primary">
    <div class="container">
      <div class="flex item-center gap-4">
        <h3 class="text-white text-4xl">If you have any question or Enquiry feel free to contat us now</h3>
        <div class="">
          <Button class="btn_xl" to="/contact" color="white" size="lg">Contact Us Now</Button>
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
import OurWork from '~/components/pages/OurWork.vue'
import WorkProcess from '~/components/pages/WorkProcess.vue'

const config = useAppConfig()

definePageMeta({
  layout: 'homepage'
})

useHead({
  title: 'Home | ' + config.siteName,
  meta: [
    {
      name: 'description',
      content: 'Reliable & Express Logistic & Transport Solutions That Saves Your Time!'
    },
    {
      name: 'keywords',
      content: 'logistics, transport, shipping, freight forwarding, express delivery, global logistics, supply chain management, cargo services, international shipping, warehousing'
    },
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

    -webkit-transform: scale(1);
    -webkit-transition: all 0.8s ease-in-out;
    z-index: 1;
    box-shadow: 0;
    border-radius: 0;

    &:hover {
      -webkit-transform: scale(1.1);
      -webkit-transition: all 0.8s ease-in-out;
      z-index: 10;
      box-shadow: 0 0 11px 4px #0000007a;
      border-radius: 16px;
    }
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


.contact_now h3 {
  width: 50%;
}

@media (max-width: 768px) {
  .expertise {
    .card {
      min-height: 350px;
    }
  }

  .contact_now h3 {
    width: 0;
  }
}
</style>

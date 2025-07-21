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
            <svg xmlns="http://www.w3.org/2000/svg" width="52" height="52" class="text-center mx-auto text-gray-700"
              viewBox="0 0 24 24"><!-- Icon from Material Symbols by Google - https://github.com/google/material-design-icons/blob/master/LICENSE -->
              <path fill="currentColor"
                d="M5 20q-.825 0-1.412-.587T3 18v-7q0-1.85.713-3.488T5.65 4.65t2.863-1.937T12 2t3.488.713T18.35 4.65t1.938 2.863T21 11v10q0 .825-.587 1.413T19 23h-6q-.425 0-.712-.288T12 22t.288-.712T13 21h6v-1h-2q-.825 0-1.412-.587T15 18v-4q0-.825.588-1.412T17 12h2v-1q0-2.9-2.05-4.95T12 4T7.05 6.05T5 11v1h2q.825 0 1.413.588T9 14v4q0 .825-.587 1.413T7 20z" />
            </svg>
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Quick Support</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
          </div>
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <svg xmlns="http://www.w3.org/2000/svg" width="52" height="52" class="text-center mx-auto text-gray-700"
              viewBox="0 0 24 24"><!-- Icon from Material Symbols by Google - https://github.com/google/material-design-icons/blob/master/LICENSE -->
              <path fill="currentColor"
                d="M3.7 10q0 1.45.488 2.775t1.387 2.45q.225.275.225.625t-.25.6t-.612.238t-.588-.288q-1.125-1.35-1.737-2.987T2 10t.613-3.412T4.35 3.6q.225-.275.588-.288t.612.238t.25.6t-.225.625q-.9 1.125-1.387 2.45T3.7 10M7 10q0 .8.225 1.525T7.9 12.9q.2.275.2.638t-.25.612t-.6.25t-.55-.275q-.675-.875-1.037-1.937T5.3 10t.363-2.187T6.7 5.875q.2-.275.55-.275t.6.25t.25.613t-.2.637q-.45.65-.675 1.375T7 10m4 10v-7.7q-.675-.3-1.088-.925T9.5 10q0-1.05.725-1.775T12 7.5t1.775.725T14.5 10q0 .75-.413 1.375T13 12.3V20q0 .425-.288.713T12 21t-.712-.288T11 20m6-10q0-.8-.225-1.525T16.1 7.1q-.2-.275-.2-.638t.25-.612t.6-.25t.55.275q.675.875 1.038 1.938T18.7 10t-.363 2.188t-1.037 1.937q-.2.275-.55.275t-.6-.25t-.25-.612t.2-.638q.45-.65.675-1.375T17 10m3.3 0q0-1.45-.488-2.775t-1.387-2.45Q18.2 4.5 18.2 4.15t.25-.6t.613-.237t.587.287q1.125 1.35 1.738 2.988T22 10t-.612 3.413T19.65 16.4q-.225.275-.587.288t-.613-.238t-.25-.6t.225-.625q.9-1.125 1.388-2.45T20.3 10" />
            </svg>
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Real-Time Tracking</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
          </div>
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <svg xmlns="http://www.w3.org/2000/svg" width="52" height="52" class="text-center mx-auto text-gray-700"
              viewBox="0 0 24 24"><!-- Icon from Material Symbols by Google - https://github.com/google/material-design-icons/blob/master/LICENSE -->
              <path fill="currentColor"
                d="M7 20q-1.25 0-2.125-.875T4 17H2.725q-.425 0-.713-.288T1.725 16t.288-.712t.712-.288h2.05q.425-.475 1-.737T7 14t1.225.263t1 .737H13.4l2.1-9H5.75q-.425 0-.712-.288T4.75 5t.288-.712T5.75 4h11q.5 0 .8.375t.175.85L17.075 8H19q.475 0 .9.213t.7.587l1.875 2.475q.275.35.35.763t0 .837L22.15 16.2q-.075.35-.35.575t-.625.225H20q0 1.25-.875 2.125T17 20t-2.125-.875T14 17h-4q0 1.25-.875 2.125T7 20m8.925-7h4.825l.1-.525L19 10h-2.375zm-2.475 1.825l.163-.725q.162-.725.412-1.775q.075-.325.15-.6t.125-.55l.163-.725q.162-.725.412-1.775t.413-1.775l.162-.725L15.5 6l-2.1 9zm-11.7-1.5q-.425 0-.712-.287t-.288-.713t.288-.712t.712-.288h3.5q.425 0 .713.288t.287.712t-.288.713t-.712.287zm2-3.65q-.425 0-.712-.288t-.288-.712t.288-.712t.712-.288h4.5q.425 0 .713.288t.287.712t-.288.713t-.712.287zM7 18q.425 0 .713-.288T8 17t-.288-.712T7 16t-.712.288T6 17t.288.713T7 18m10 0q.425 0 .713-.288T18 17t-.288-.712T17 16t-.712.288T16 17t.288.713T17 18" />
            </svg>
            <h3 class="mt-6 text-xl font-bold text-gray-900 font-pj">Quick Support</h3>
            <p class="mt-5 text-base text-gray-600 font-pj">Providing the best transport and shipping services currently
              available allover the world. Our skilled</p>
          </div>
          <div class="p-4 pt-8 pb-8 rounded-2xl border border-gray-300">
            <svg xmlns="http://www.w3.org/2000/svg" width="52" height="52" class="text-center mx-auto text-gray-700"
              viewBox="0 0 24 24"><!-- Icon from Material Symbols by Google - https://github.com/google/material-design-icons/blob/master/LICENSE -->
              <path fill="currentColor"
                d="M3 20q-.825 0-1.412-.587T1 18V7h2v11h17v2zm4-4q-.825 0-1.412-.587T5 14V6q0-.825.588-1.412T7 4h14q.825 0 1.413.588T23 6v8q0 .825-.587 1.413T21 16zm2-2q0-.825-.587-1.412T7 12v2zm10 0h2v-2q-.825 0-1.412.588T19 14m-5-1q1.25 0 2.125-.875T17 10t-.875-2.125T14 7t-2.125.875T11 10t.875 2.125T14 13M7 8q.825 0 1.413-.587T9 6H7zm14 0V6h-2q0 .825.588 1.413T21 8" />
            </svg>
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
  <svg
    class="hidden md:block absolute left-0 right-0 top-1/3 transform -translate-y-1/2 z-0"
    width="100%"
    height="150"
    viewBox="0 0 1000 150"
    preserveAspectRatio="none"
  >
    <path
      d="M0,75 C150,0 350,150 500,75 C650,0 850,150 1000,75"
      fill="none"
      stroke="#CBD5E0"
      stroke-width="2"
      stroke-dasharray="10,10"
    />
  </svg>

        <!-- Step 1 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <img src="/images/receive-package.webp" alt="Step 1"
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
            <img src="/images/receive-package.webp" alt="Step 2"
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
            <img src="/images/receive-package.webp" alt="Step 3"
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

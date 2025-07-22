<template>
    <section class="work_process py-40 ">
    <div class="container">
      <h3 class="uppercase text-gray-700 mb-8 text-center">Work Process</h3>
      <h2 class="text-center text-5xl mb-10">Today’s Fast-Paced World's Efficient Logistics.</h2>
      <div class="relative flex flex-col md:flex-row items-center justify-between gap-12 md:gap-6">
        <!-- Wavy Dashed Line (SVG) -->
        <NuxtImg src="/images/wave.svg" alt="Wavy Dashed Line"
          class="hidden md:block absolute left-0 right-0 top-1/3 transform -translate-y-1/2 z-0" />

        <!-- Step 1 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <NuxtImg src="/images/receive_package.webp" alt="Step 1" class="w-60 h-60 rounded-full object-cover border-4 border-white shadow-md 
              hover:shadow-lg  duration-[0.5s] ease-in-out transform hover:scale-105" loading="lazy" />
            <span
              class="absolute top-4 right-4 bg-yellow-400 w-10 h-10 rounded-full  flex items-center justify-center font-bold text-black text-lg">1</span>
              <span
              class="absolute top-4 right-4 w-10 h-10 rounded-full animate-ping flex items-center justify-center border-2 border-amber-400 "></span>
          </div>
          <h3 class="text-xl font-semibold mt-6">Step 1: Receive Package</h3>
          <p class="text-gray-600 text-lg mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit. Mauris nullam
            the as integer.</p>
        </div>

        <!-- Step 2 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <NuxtImg src="/images/transport.webp" alt="Step 2"
              class="w-60 h-60 rounded-full object-cover border-4 border-white shadow-md duration-[0.5s] ease-in-out transform hover:scale-105"
              loading="lazy" />
            <span
              class="absolute top-4 right-4 bg-yellow-400 w-10 h-10 rounded-full  flex items-center justify-center font-bold text-black text-lg">2</span>
            <span
              class="absolute top-4 right-4 w-10 h-10 rounded-full animate-ping flex items-center justify-center border-2 border-amber-400 "></span>
          </div>
          <h3 class="text-xl font-semibold mt-6">Step 2: Transport Packages</h3>
          <p class="text-gray-600 text-lg mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit. Mauris nullam
            the as integer.</p>
        </div>

        <!-- Step 3 -->
        <div class="flex flex-col items-center text-center z-10 max-w-xs">
          <div class="relative">
            <NuxtImg src="/images/deliver.webp" alt="Step 3"
              class="w-60 h-60 rounded-full object-cover border-4 border-white shadow-md duration-[0.5s] ease-in-out transform hover:scale-105"
              loading="lazy" />
            <span
              class="absolute top-4 right-4 bg-yellow-400 w-10 h-10 rounded-full  flex items-center justify-center font-bold text-black text-lg">3</span>
              <span
              class="absolute top-4 right-4 w-10 h-10 rounded-full animate-ping flex items-center justify-center border-2 border-amber-400 "></span>
          </div>
          <h3 class="text-xl font-semibold mt-6">Step 3: Deliver Packages</h3>
          <p class="text-gray-600 text-lg mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit. Mauris nullam
            the as integer.</p>
        </div>
      </div>
    </div>
  </section>
</template>
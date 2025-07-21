
<template>
  <section class="sm:px-6 lg:px-8">
    <div class="testimonial_wrapper | lg:w-5xl mx-auto w-full text-center">
      <Swiper
        :modules="[Navigation, Pagination, Autoplay]"
        :pagination="{ clickable: true }"
        :navigation="true"
        :autoplay="{ delay: 5000 }"
        loop
        class="testimonial_content | w-[100%] relative"
      >
        <SwiperSlide
          v-for="(testimonial, index) in testimonials"
          :key="index"
          class=""
        >
          <blockquote
            class="flex flex-col items-center justify-center px-4 sm:px-8 h-full"
          >
            <p
              class="text-base sm:text-lg md:text-xl lg:text-2xl font-medium text-gray-700  max-w-3xl mx-auto"
            >
              “{{ testimonial.message }}”
            </p>
            <footer class="mt-6 sm:mt-8 text-center">
              <p class="text-base font-semibold">{{ testimonial.name }}</p>
              <p class="text-sm text-gray-500">{{ testimonial.title }}</p>
            </footer>
          </blockquote>
        </SwiperSlide>

      </Swiper>
    </div>
  </section>
</template>


<script setup>
import { Swiper, SwiperSlide } from 'swiper/vue'
import { Navigation, Pagination, Autoplay } from 'swiper/modules'

// Must import styles for arrows to work!
import 'swiper/css'
import 'swiper/css/navigation'
import 'swiper/css/pagination'

const testimonials = [
    {
        message:
            'The quality and luster of the gold looks as good as new even years after it was applied. We are very satisfied with the quality and service provide by Paradise Leafing Art.',
        name: 'Ravi Ohri',
        title: 'Ohris Banjara',
    },
    {
        message: 'We are extremely satisfied with the appearance and texture of the gold. It really enhances the look and class of the space it was applied in. Thanks to Paradise Leafing Art for their service.',
        name: 'Yusuf',
        title: 'ITC maratha Andheri',
    },
    {
        message: 'I love the grand look the leafing has given to my bungalow. The work was completed within a specific amount of time with good craftsmanship and service.',
        name: 'VV. Vinayak',
        title: 'Director',
    },
    {
        message: 'Would highly recommend Paradise Leafing Art for any leafing work. They are very efficient and precise in their work. Completely transformed my showroom and gave it a glamorous look with their craftsmanship.',
        name: 'Rocky S',
        title: 'Fashion Designer',
    },
    {
        message: 'Truly grateful to Paradise Leafing Art for their services in beautifying my showroom. Totally transformed and adorned the look within the time limit.',
        name: 'Shantanu Nikhil',
        title: 'Fashion Designer',
    },
]
</script>

<style>
.swiper-button-prev:after,
.swiper-button-next:after {
    color: #333;
    top: 50%;
    transform: translateY(-50%);
    z-index: 10;
    font-size: 32px;
}

.swiper-button-prev {
    left: 5px;
}

.swiper-button-prev {
    right: 5px;
}

.swiper-pagination {
    display: none;
}
/* 
.swiper-slide p{
    width: 80vw;
} */




@media (max-width: 640px) {

    /* .swiper-button-prev,
    .swiper-button-next {
        display: none;
    } */

    .testimonial_content {
    width: 100vw;
}
}
</style>

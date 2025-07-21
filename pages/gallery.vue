<template>
      <div class="gallery-page">
            <!-- Hero Section -->
            <section class="gallery-hero">
                  <div class="container">
                        <h2>Gallery</h2>
                  </div>
            </section>

            <!-- Categories -->
            <section class="gallery-categories">
                  <div class="container">
                        <h3>Select a Category</h3>
                        <div class="categories-grid">
                              <button v-for="cat in categories" :key="cat.name"
                                    :class="['category-btn', { active: selectedCategory === cat.name }]"
                                    @click="selectedCategory = cat.name">
                                    <span>{{ cat.name }}</span>
                              </button>
                        </div>
                  </div>
            </section>

            <!-- Images -->
            <section v-if="selectedCategory" class="gallery-images">
                  <div class="container">
                        <h3>{{ selectedCategory }} Images</h3>
                        <div class="images-grid">
                              <div v-for="img in images[selectedCategory]" :key="img.src" class="gallery-image-wrapper"
                                    @click="openLightbox(img)">
                                    <NuxtImg :src="img.src" :alt="img.alt" class="gallery-image" :format="webp"
                                          densities="x1" sizes="sm:300px" />
                                    <div class="image-caption">{{ img.alt }}</div>
                              </div>
                        </div>
                        <!-- <button class="back-btn" @click="selectedCategory = null">
                              Back to Categories
                        </button> -->
                  </div>
            </section>

            <!-- Lightbox Modal -->
            <div v-if="lightboxImage" class="lightbox" @click.self="closeLightbox">
                  <button class="arrow left" @click.stop="prevImage" :disabled="lightboxIndex === 0">‹</button>

                  <NuxtImg :src="lightboxImage.src" :alt="lightboxImage.alt" class="lightbox-img" :format="webp"
                        densities="x1" sizes="sm:300px lg:1000px" />
                  <p class="lightbox-caption">{{ lightboxImage.alt }}</p>

                  <button class="arrow right" @click.stop="nextImage"
                        :disabled="lightboxIndex === images[selectedCategory].length - 1">›</button>
            </div>

      </div>
</template>

<script setup>
import { ref, computed } from 'vue'

const selectedCategory = ref('Bunglow')
const lightboxIndex = ref(null)

const lightboxImage = computed(() => {
      if (lightboxIndex.value === null) return null
      return images[selectedCategory.value][lightboxIndex.value]
})

const categories = [
      { name: 'Bunglow', icon: '/images/gallery/bunglow-1.webp' },
      { name: 'Furniture', icon: '/images/gallery/bunglow-2.webp' },
      { name: 'Warehousing', icon: '/images/gallery/furniture-41.webp' },
      { name: 'Fleet', icon: '/images/gallery/mandir-2-1.webp' },
]

const images = {
      Bunglow: [
            { src: '/images/gallery/temp.jpg', alt: 'Our Team' },
            { src: '/images/gallery/temp.jpg', alt: 'Our Team' },
      ],
      Furniture: [
            { src: '/assets/images/shipping.jpg', alt: 'Shipping Furniture' },
            { src: '/assets/images/ocean-shipping.jpg', alt: 'Ocean Shipping' },
            { src: '/assets/images/air-freight.jpg', alt: 'Air Freight' },
      ],
      Warehousing: [
            { src: '/assets/images/warehousing.jpg', alt: 'Warehouse Facility' },
      ],
      Fleet: [
            { src: '/assets/images/truck.jpg', alt: 'Logistics Truck' },
      ],
}

function openLightbox(img) {
      const index = images[selectedCategory.value].findIndex(i => i.src === img.src)
      lightboxIndex.value = index
}

function closeLightbox() {
      lightboxIndex.value = null
}

function prevImage() {
      if (lightboxIndex.value > 0) {
            lightboxIndex.value--
      }
}

function nextImage() {
      if (lightboxIndex.value < images[selectedCategory.value].length - 1) {
            lightboxIndex.value++
      }
}
</script>



<style scoped>
.gallery-page {
      .gallery-hero {
            background: #1abc9c;
            color: white;
            text-align: center;
            padding: 4rem 1rem 2rem 1rem;

            h2 {
                  font-size: 2.5rem;
                  margin-bottom: 0.5rem;
            }

            p {
                  font-size: 1.2rem;
            }
      }

      .gallery-categories {
            padding: 2rem 0;

            h3 {
                  text-align: center;
                  margin-bottom: 2rem;
            }

            .categories-grid {
                  display: flex;
                  flex-wrap: wrap;
                  gap: 2rem;
                  justify-content: center;

                  .category-btn {
                        background: #fff;
                        border: 2px solid #1abc9c;
                        border-radius: 8px;
                        padding: 1rem 2rem;
                        display: flex;
                        flex-direction: column;
                        align-items: center;
                        cursor: pointer;
                        transition: background 0.2s, border 0.2s;

                        &.active,
                        &:hover {
                              background: #1abc9c;
                              color: #fff;
                        }

                        .category-icon {
                              width: 60px;
                              height: 60px;
                              object-fit: cover;
                              border-radius: 50%;
                              margin-bottom: 0.5rem;
                        }
                  }
            }
      }

      .gallery-images {
            padding: 2rem 0;

            h3 {
                  text-align: center;
                  margin-bottom: 2rem;
            }

            .images-grid {
                  display: grid;
                  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
                  gap: 2rem;

                  .gallery-image-wrapper {
                        background: #fff;
                        border-radius: 8px;
                        box-shadow: 0 2px 8px rgba(0, 0, 0, 0.07);
                        padding: 1rem;
                        text-align: center;

                        .gallery-image {
                              width: 100%;
                              border-radius: 4px;
                              margin-bottom: 0.5rem;
                        }

                        .image-caption {
                              color: #7f8c8d;
                              font-size: 0.95rem;
                        }
                  }
            }

            .back-btn {
                  display: block;
                  margin: 2rem auto 0 auto;
                  background: #1abc9c;
                  color: #fff;
                  border: none;
                  border-radius: 4px;
                  padding: 0.75rem 2rem;
                  font-size: 1rem;
                  cursor: pointer;
                  transition: background 0.2s;

                  &:hover {
                        background: #159c82;
                  }
            }
      }
}
</style>

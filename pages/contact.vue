<template>
      <DefaultHeader title="Contact us" image="/images/about_bg_header.webp" class="bg-fixed bg-bottom w-full" />
      <section class="about_us | py-32">
            <div class="container">

                  <div class="md:flex">
                        <!-- Left Side -->
                        <div class="md:w-2/3">
                              <h2 class="flex items-center gap-3 text-[24px] lg:text-4xl">Get in touch
                                    <span>
                                          <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                                    </span>
                              </h2>
                              <p class="text-gray-700">
                                    We pride ourselves on providing the best transport & sharing
                                    services available allover the world.
                              </p>
                              <div class="py-4 text-gray-700 mt-3">
                                    <p class="uppercase text-2xl font-bold">ZAK Logistics</p>
                                    <p>
                                          Unit No. 211, Lodha Supremus<br />
                                          MIDC Plot No.: F4 & 4/1<br />
                                          Road No. 22, Wagle Estate,<br />
                                          Nr. New Passport Office<br />
                                          Thane West: 400 604
                                    </p>
                              </div>
                              <div class="py-4 text-gray-700">
                                    <div class="flex items-center py-2">
                                          <Icon name="mdi:phone" class="text-2xl mr-2" />(Landline) 022-25870821 / 22 /
                                          23<br />
                                    </div>
                                    <div class="flex items-center py-2">
                                          <Icon name="mynaui:mobile-solid" class="text-2xl mr-2" />+91 9819617674 / +91
                                          8108395511
                                    </div>
                                    <div class="flex items-center py-2">
                                          <Icon name="mdi:fax" class="text-2xl mr-2" />(Fax) 022-25870820
                                    </div>
                                    <div class="flex items-center py-2">
                                          <Icon name="mdi:mail" class="text-2xl mr-2" />sales@zaklogistics.com
                                    </div>

                              </div>
                              <SocialIcons />

                        </div>

                        <div class="md:w-1/3 py-5 px-0 lg:p-10 flex flex-col justify-between">
                              <form class="space-y-6">
                                    <div class="">
                                          <!-- Full Name -->
                                          <div class="mb-6">
                                                <input type="text" name="fullName" placeholder="Full Name"
                                                      class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800"
                                                      required />
                                          </div>

                                          <!-- Email -->
                                          <div class="mb-6">
                                                <input type="email" name="email" placeholder="Email Address"
                                                      class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800"
                                                      required />
                                          </div>

                                          <!-- Mobile Number -->
                                          <div class="mb-6">
                                                <input type="tel" name="mobile" placeholder="Mobile Number"
                                                      class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800"
                                                      required />
                                          </div>

                                          <!-- Company -->
                                          <div class="mb-6">
                                                <input type="text" name="company" placeholder="Company"
                                                      class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800"
                                                      required />
                                          </div>
                                          <!-- Message -->
                                          <div class="mb-6">
                                                <textarea id="message" name="message"
                                                      class="h-32 w-full resize-none rounded border border-gray-300 bg-white py-1 px-3 text-base leading-6 text-gray-700 outline-none transition-colors duration-200 ease-in-out focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200"
                                                      required>Message</textarea>
                                          </div>



                                    </div>

                                    <!-- Submit -->
                                    <div>
                                          <button type="submit"
                                                class="w-full py-3 px-6 bg-[#147CB5] text-white font-medium rounded-lg shadow-sm hover:bg-red-700 transition duration-300">
                                                Contact us
                                          </button>
                                    </div>
                              </form>
                        </div>

                        <!-- Right Side - Form -->

                  </div>

            </div>
      </section>

      <section>
            <div class="relative w-full h-[600px]">
                  <iframe class="absolute top-0 left-0 w-full h-full"
                        src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d3767.9560909023285!2d72.94673076541427!3d19.197120081374084!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1sLodha%20Supremus%20MIDC%20Plot%20No.%3A%20F4%20%20thane%26%204%2F1!5e0!3m2!1sen!2sin!4v1753346530621!5m2!1sen!2sin"
                        frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"
                        loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                  </iframe>

            </div>
      </section>



      <section class="pre_footer | bg-gray-900">
            <PreFooter />
      </section>

</template>

<script setup>
import DefaultHeader from '~/components/layout/DefaultHeader.vue'
import PreFooter from '~/components/layout/PreFooter.vue'
import SocialIcons from '~/components/layout/Social.vue'


const config = useAppConfig()

useHead({
      title: 'Contat us | ' + config.siteName,
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
.right_box {
      background-image: url('/images/enquiry.webp');
      background-size: cover;
      background-position: center;
      height: 100%;
      overflow: hidden;


}
</style>

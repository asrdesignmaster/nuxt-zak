<template>
    <DefaultHeader title="Enquiry" image="/images/about_bg_header.webp" class="bg-fixed bg-bottom w-full" />
    <section class="about_us | py-32">
        <div class="container">
            <div class="flex justify-center flex-col items-center gap-4">
                <h2 class="flex items-center gap-3 text-[24px] lg:text-4xl">Safe and secure delivery
                    <span>
                        <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                    </span>
                </h2>
                <p class="text-center">We pride ourselves on providing the best transport & sharing services available
                    allover the world.</p>
            </div>


            <div class="md:flex mt-28">
                <!-- Left Side -->
                <div class="md:w-1/3 p-5 lg:p-10 bg-primary text-white flex flex-col justify-between">
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

                            <!-- Course Selection -->
                            <div class="mb-6">
                                <select name="courses"
                                    class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800 bg-white"
                                    required>
                                    <option value="" disabled selected>Select Freight Type</option>

                                    <!-- By Mode of Transport -->
                                    <option value="road">Road Freight</option>
                                    <option value="rail">Rail Freight</option>
                                    <option value="air">Air Freight</option>
                                    <option value="sea">Sea/Ocean Freight</option>
                                    <option value="inland_waterway">Inland Waterway Freight</option>
                                    <option value="pipeline">Pipeline Freight</option>

                                    <!-- By Load Type -->
                                    <option value="fcl">FCL (Full Container Load)</option>
                                    <option value="lcl">LCL (Less than Container Load)</option>
                                    <option value="ftl">FTL (Full Truckload)</option>
                                    <option value="ltl">LTL (Less than Truckload)</option>

                                    <!-- By Cargo Type -->
                                    <option value="general">General Cargo</option>
                                    <option value="bulk_dry">Bulk Cargo – Dry</option>
                                    <option value="bulk_liquid">Bulk Cargo – Liquid</option>
                                    <option value="break_bulk">Break Bulk Cargo</option>
                                    <option value="refrigerated">Refrigerated / Perishable Goods</option>
                                    <option value="hazardous">Hazardous Materials (HAZMAT)</option>
                                    <option value="oversized">Oversized / Project Cargo</option>
                                </select>
                            </div>
                            <!-- City of Departure -->
                            <div class="mb-6">
                                <input type="text" name="cityDeparture" placeholder="City of Departure"
                                    class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800"
                                    required />
                            </div>
                            <!-- Delivery City -->
                            <div class="mb-6">
                                <input type="text" name="deliveryCity" placeholder="Delivery City"
                                    class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-800"
                                    required />
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <!-- Weight -->
                                <div>
                                    <input type="number" name="weight" placeholder="Weight"
                                        class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-ring-gray-800"
                                        required />
                                </div>
                                <!-- Height -->
                                <div>
                                    <input type="number" name="height" placeholder="Height"
                                        class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-ring-gray-800"
                                        required />
                                </div>
                                <!-- Width -->
                                <div>
                                    <input type="number" name="width" placeholder="Width"
                                        class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-ring-gray-800"
                                        required />
                                </div>
                                <!-- Length -->
                                <div>
                                    <input type="number" name="length" placeholder="Length"
                                        class="w-full px-4 py-3 bg-white text-gray-900 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-gray-700 focus:border-gray-ring-gray-800"
                                        required />
                                </div>

                                <div class="flex items-center">
                                    <input type="radio" name="deliveryType" id="fragile" class="h-5 w-5" />
                                    <label for="fragile" class="pl-3  text-white">
                                        Fragile
                                    </label>
                                </div>
                                <div class="flex items-center">
                                    <input type="radio" name="deliveryType" id="packaging" class="h-5 w-5" />
                                    <label for="packaging" class="pl-3  text-white">
                                        Packaging
                                    </label>
                                </div>
                                <div class="flex items-center">
                                    <input type="radio" name="deliveryType" id="expDelivery" class="h-5 w-5" />
                                    <label for="expDelivery" class="pl-3  text-white">
                                        Express Delivery
                                    </label>
                                </div>
                                <div class="flex items-center">
                                    <input type="radio" name="deliveryType" id="insurance" class="h-5 w-5" />
                                    <label for="insurance" class="pl-3  text-wite">
                                        Insurance
                                    </label>
                                </div>
                            </div>

                        </div>

                        <!-- Submit -->
                        <div>
                            <button type="submit"
                                class="w-full py-3 px-6 bg-[#147CB5] text-white font-medium rounded-lg shadow-sm hover:bg-red-700 transition duration-300">
                                Submit Enquiry
                            </button>
                        </div>
                    </form>
                </div>

                <!-- Right Side - Form -->
                <div class="md:w-2/3">
                    <div class="right_box"></div>
                </div>
            </div>

        </div>
    </section>


    <ContactNow />

    <section class="pre_footer | bg-gray-900">
        <PreFooter />
    </section>

</template>

<script setup>
import DefaultHeader from '~/components/layout/DefaultHeader.vue'
import PreFooter from '~/components/layout/PreFooter.vue'
import ContactNow from '~/components/pages/ContactNow.vue'


const config = useAppConfig()

useHead({
    title: 'Enquiry | ' + config.siteName,
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

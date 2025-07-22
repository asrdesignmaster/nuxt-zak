<template>
    <DefaultHeader title="About Us" image="/images/about_bg_header.webp" class="bg-fixed bg-bottom w-full" />
    <section class="about_us | pt-32">
        <div class="container">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-2">
                <div class="flex  items-center">
                    <NuxtImg src="/images/about_us.webp" format="webp" densities="1" class="rounded-xl" />
                </div>
                <div class="py-20">
                    <h2 class="flex items-center gap-3">Here to Help Your Business Need <span>
                            <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                        </span></h2>
                    <p class="text-xl text-gray-500">ZAK Logistics is an innovative and energetic shipping / Freight
                        forwarding company. </p>
                    <p class="text-xl text-gray-500 pt-4">which has rapidly grown in it's range of service turnover and
                        geographic coverage establishing itself as a leading forwarder in India.</p>
                    <p class="text-xl text-gray-500 pt-4">
                        ZAK Logistics is much more than getting a piece of freight from one point to another. We define
                        logistics as that part of the supply chain process that plans, implements, and controls the
                        efficient, effective flow and storage of goods, services, and related information from the point
                        of origin to the point of consumption in order to meet customers.</p>
                    <p class="text-xl text-gray-500 pt-4">
                        Our job is to make sure that from raw material to finished goods sitting on the retail shelf, we
                        provide the critical services and information necessary to give our clients a competitive
                        advantage in business.</p>
                    <p>
                        We follow a tried and tested strategy with a clear focus on international air and ocean
                        transport and supply chain management solutions. This marks us out from our main competitors.
                    </p>
                    <p>
                        Our quality system is an integrated management instrument which assures the steady optimization
                        of the quality of our services. Furthermore we believe in highly trained, skilled and motivated
                        staff in driving daily performance.</p>
                </div>

            </div>

        </div>
    </section>

    <section class="mission_vision | py-32">
        <div class="container">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-4">
                <div class="">
                    <h2 class="flex items-center gap-3">Mission
                        <span>
                            <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                        </span>
                    </h2>
                    <p class="text-xl text-gray-500">ZAK Logistics is much more than getting a piece of freight from one
                        point to another. We define logistics as that part of the supply chain process that plans,
                        implements, and controls the efficient, effective flow and storage of goods, services, and
                        related information from the point of origin to the point of consumption in order to meet
                        customers.</p>
                </div>
                <div class="">
                    <h2 class="flex items-center gap-3">Vission
                        <span>
                            <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                        </span>
                    </h2>
                    <p class="text-xl text-gray-500">ZAK Logistics is much more than getting a piece of freight from one
                        point to another. We define logistics as that part of the supply chain process that plans,
                        implements, and controls the efficient, effective flow and storage of goods, services, and
                        related information from the point of origin to the point of consumption in order to meet
                        customers.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="sectors | py-32 text-center">
        <div class="container">
            <h2 class="text-6xl mb-6">Our Major Expertise Sectors</h2>
            <div class="">

                <div class="flex flex-col w-full mb-5 sm:flex-row">
                    <div class="w-full mb-6 sm:mb-0 sm:w-1/2">
                        <div class="h-full ml-0 mr-0 sm:mr-10">
                            <div
                                class="h-full px-5 py-10 bg-white shadow-xl shadow-gray-200 border border-gray-200 rounded-lg flex flex-col item-center">
                                <div class="flex items-center -mt-1">
                                    <h3 class="my-2 text-lg font-bold text-gray-800">EUROPE</h3>
                                </div>
                                <p class="text-gray-600 text-left">UK, Italy, Spain, Germany, Denmark, Poland, Sweden,
                                    Portugal, Switzerland, Bulgaria, France, Austria, Hungary, Netherlands, Greece,
                                    Belgium, Turkey.</p>
                            </div>
                        </div>
                    </div>
                    <div class="w-full mb-6 sm:mb-0 sm:w-1/2 flex flex-col gap-5">
                        <div class="h-1/2 ml-0 mr-0 sm:mr-10">
                            <div
                                class="h-full px-5 py-1 bg-white shadow-xl shadow-gray-200 border border-gray-200 rounded-lg ">
                                <div class="flex items-center -mt-1">
                                    <h3 class="my-2 text-lg font-bold text-gray-800">MIIDDLE EAST</h3>
                                </div>
                                <p class="text-gray-600 text-left">UAE, Saudi Arabia, Egypt</p>
                            </div>
                        </div>
                        <div class="h-1/2 ml-0 mr-0 sm:mr-10">
                            <div
                                class="h-full px-5 py-1 bg-white shadow-xl shadow-gray-200 border border-gray-200 rounded-lg">
                                <div class="flex items-center -mt-1">
                                    <h3 class="my-2 text-lg font-bold text-gray-800">EAST</h3>
                                </div>
                                <p class="text-gray-600 text-left">USA, Canada, Brazil, Argentina</p>
                            </div>
                        </div>
                    </div>
                    <div class="w-full sm:w-1/2">
                        <div class="h-full ml-0 md:mr-10">
                            <div
                                class="h-full px-5 py-10 bg-white shadow-xl border border-gray-200 rounded-lg flex flex-col item-center">
                                <div class="flex items-center -mt-1">
                                    <h3 class="my-2 text-lg font-bold text-gray-800">FAR-EAST</h3>
                                </div>
                                <p class="text-gray-600 text-left">China, Singapore, Malaysia, Japan, Thailand, Vietnam,
                                    Taiwan, Philippines, Indonesia, South-Korea & Australia, New Zealand
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <OurWork />

    <WorkProcess />

    <section class="pre_footer | bg-gray-900">
        <PreFooter />
    </section>

</template>

<script setup>
import DefaultHeader from '~/components/layout/DefaultHeader.vue'
import OurWork from '~/components/pages/OurWork.vue'
import WorkProcess from '~/components/pages/WorkProcess.vue'
import PreFooter from '~/components/layout/PreFooter.vue'

const config = useAppConfig()

useHead({
    title: 'About us | ' + config.siteName,
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

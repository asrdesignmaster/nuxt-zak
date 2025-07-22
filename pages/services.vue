<template>
    <DefaultHeader title="Services" image="/images/about_bg_header.webp" class="bg-fixed bg-bottom w-full" />
    <section class="about_us | py-32">
        <div class="container">
            <div class="flex justify-center flex-col items-center gap-4">
                <h2 class="flex items-center gap-3 text-[24px] lg:text-4xl">Safe and secure delivery
                    <span>
                        <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                    </span>
                </h2>
                <p class="text-center">With its specialized global services and advanced communications
                    technology network and tracking systems, <br />ZAK LOGISTICS. offers its customers a broad range of
                    Total
                    Logistics Solutions:</p>
            </div>
            <div class="grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-3  [&>img:not(:first-child)]:mt-8 mt-8">
                <div class="ocean_freight | relative">
                    <div class="freight_curtain"></div>
                    <h3 class="text-center text-white text-2xl">Ocean Freight Forwarding</h3>
                </div>
                <div class="ocean_freight | relative">
                    <div class="freight_curtain"></div>
                    <h3 class="text-center text-white text-2xl">Road Freight Forwarding</h3>
                </div>
                <div class="ocean_freight | relative">
                    <div class="freight_curtain"></div>
                    <h3 class="text-center text-white text-2xl">Air Freight Forwarding</h3>
                </div>
                <div class="ocean_freight | relative">
                    <div class="freight_curtain"></div>
                    <h3 class="text-center text-white text-2xl">Road Freight Forwarding</h3>
                </div>
                <div class="ocean_freight | relative">
                    <div class="freight_curtain"></div>
                    <h3 class="text-center text-white text-2xl">Air Freight Forwarding</h3>
                </div>
                <div class="ocean_freight | relative">
                    <div class="freight_curtain"></div>
                    <h3 class="text-center text-white text-2xl">Ocean Freight Forwarding</h3>
                </div>
            </div>
        </div>
    </section>

    <section class="mission_vision |  bg-gray-900">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4 ">
            <div class="">
                <NuxtImg src="/images/international.webp" alt="international" densities="x1" class="w-full h-60 lg:h-full object-cover" />
            </div>
            <div class="py-16 px-4 lg:px-0">
                <div class="pl-0 lg:pl-3 ">
                    <h2 class="flex items-center gap-3 text-white text-center lg:text-left">International Air & Sea
                        Service
                        Provider </h2>
                    <p
                        class="text-xl text-white font-[weight:var(--font-weight-light)] w-full lg:max-w-2xl  text-center lg:text-left">
                        ZAK Logistics offers a wide range of services with the scheduling and budget options that meet
                        your
                        requirements. Customers can select suitable schedules,
                        costs and routes to any number of key destinations around the world. Planways support every
                        logistical need of exporters and importers on a global basis, from packing, pick-up, and
                        documentation, to customs clearance and delivery to the final destination.</p>
                    <p>Planways gives the complete solution to the customer for their required needs with the suitable
                        options.</p>
                </div>
            </div>
        </div>
    </section>

    <WorkProcess />

    <ContactNow />

    <section class="pre_footer | bg-gray-900">
        <PreFooter />
    </section>

</template>

<script setup>
import DefaultHeader from '~/components/layout/DefaultHeader.vue'
import WorkProcess from '~/components/pages/WorkProcess.vue'
import PreFooter from '~/components/layout/PreFooter.vue'
import ContactNow from '~/components/pages/ContactNow.vue'


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

<style scoped>
.ocean_freight {
    background-image: url('/images/ocean_freight.webp');
    background-size: cover;
    background-position: center;
    height: 280px;
    border-radius: 12px;
    overflow: hidden;

    .freight_curtain {
        mix-blend-mode: multiply;
        opacity: 1;
        background: linear-gradient(0deg, #154765 0%, rgba(216, 216, 216, 0) 100%);
        height: 150px;
        position: absolute;
        bottom: 0;
        width: 100%;
    }

    h3 {
        position: absolute;
        bottom: 16px;
        width: 100%;
    }
}
</style>

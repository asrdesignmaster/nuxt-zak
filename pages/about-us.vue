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
                    <p class="text-xl text-gray-500">ZAK Logistics is much more than getting a piece of freight from one point to another. We define logistics as that part of the supply chain process that plans, implements, and controls the efficient, effective flow and storage of goods, services, and related information from the point of origin to the point of consumption in order to meet customers.</p>
                </div>
                <div class="">
                    <h2 class="flex items-center gap-3">Vission
                        <span>
                            <Icon name="famicons:airplane-sharp" class="text-2xl  text-primary" />
                        </span>
                    </h2>
                    <p class="text-xl text-gray-500">ZAK Logistics is much more than getting a piece of freight from one point to another. We define logistics as that part of the supply chain process that plans, implements, and controls the efficient, effective flow and storage of goods, services, and related information from the point of origin to the point of consumption in order to meet customers.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
import DefaultHeader from '~/components/layout/DefaultHeader.vue'
</script>

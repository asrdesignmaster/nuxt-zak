<template>
    <div class="default_header bg-cover bg-center p-0! relative" :style="{ backgroundImage: `url(${image})` }">
        <div class="curtain z-10 opacity-45"></div>
        <div class="container h-48">
            <div class="relative w-full h-full">
                <div class="absolute left-0 -bottom-2">
                    <h1 class="text-7xl font-bold text-white tracking-wide uppercase relative z-50">

                        {{ title }}
                        
                    </h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
defineProps({
    title: {
        type: String,
        default: null,
    },
    image: {
        type: String,
        default: '',
    },
})
</script>

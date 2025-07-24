<template>
    <NuxtLink to="/" @click="$emit('menu-item-clicked')">Home</NuxtLink>
    <NuxtLink to="/about-us" class="w-fit" @click="$emit('menu-item-clicked')">About <span class="sr-only">Go to our About us page</span></NuxtLink>
    <NuxtLink to="/services" class="w-fit" @click="$emit('menu-item-clicked')">Services<span class="sr-only">Go to our Services page</span></NuxtLink>
    <NuxtLink to="/enquiry" class="w-fit" @click="$emit('menu-item-clicked')">Enquiry<span class="sr-only">Go to our Enquiry page</span></NuxtLink>
    <NuxtLink to="/contact" class="w-fit" @click="$emit('menu-item-clicked')">Contact<span class="sr-only">Go to our Contact us page</span></NuxtLink>
      
</template>
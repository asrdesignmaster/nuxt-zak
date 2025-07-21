<template>
    <component
    :is="link ? NuxtLink : 'button'"
    :to="link"
    class="button"
  >
    <slot>Click Me</slot>
  </component>
</template>

<script setup>
import { NuxtLink } from '#components'

defineProps({
  link: {
    type: String,
    default: null,
  },
})
</script>

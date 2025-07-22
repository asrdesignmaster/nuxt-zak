<template>
    <section class="contact_now | py-20 bg-primary">
    <div class="container">
      <div class="flex item-center flex-col lg:flex-row gap-4">
        <h3 class="text-white text-4xl">If you have any question or Enquiry feel free to contat us now</h3>
        <div class="">
          <Button class="btn_xl" to="/contact" color="white" size="lg">Contact Us Now</Button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import Button from '~/components/common/LinkButton.vue'
import ContactNow from '~/components/pages/ContactNow.vue'

</script>

<style>

.contact_now h3 {
  width: 50%;
}

@media (max-width: 768px) {
  .contact_now {
    h3 {
    width: 100%;
    margin-bottom: 16px;
  }
  .button{
    width: 100%;
  }
  }
}
</style>
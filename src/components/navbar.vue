<template>
  <div class="absolute inset-x-0 top-0">
    <div class="px-5 lg:px-40 container mx-auto lg:flex lg:items-center justify-between lg:py-8 space-y-8 lg:space-y-0">
      <div class="lg:w-4/12">
        <ul class="lg:flex text-sm text-blue-600 space-y-4 lg:space-y-0 lg:space-x-12">
          <li><g-link to="/home/">Home</g-link></li>
          <li><g-link to="/about/">About</g-link></li>
          <li><g-link to="/contact/">Contact</g-link></li>
        </ul>
      </div>
      <div class="lg:w-4/12">
        <g-image src="~/assets/Landie.png" class="mx-auto"/>
      </div>
      <div class="lg:w-4/12 text-right">
          <base-button class="text-white py-1">Buy Now</base-button>
      </div>
    </div>
  </div>
</template>

<script>
import BaseButton from "~/components/BaseButton.vue"

export default {
  components: {
    BaseButton
  },
  methods: {
    onClick () {
      
    }
  }
}
</script>

<style>

</style>


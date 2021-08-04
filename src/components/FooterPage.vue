<template>
  <div class="bg-blue-500 absolute inset-x-0 bottom-0">
    <div class="px-5 lg:px-40 container mx-auto lg:flex lg:items-center justify-between lg:py-8 space-y-8 lg:space-y-0">
      <div class="lg:w-4/12">
        <ul class="lg:flex text-sm text-blue-600 space-y-4 lg:space-y-0 lg:space-x-12">
          <li><g-link to="/home/">@2020 Yourcompany</g-link></li>
        </ul>
      </div>
      <div class="lg:w-4/12">
        <g-image src="~/assets/Landie.png" class="lg:mx-auto"/>
      </div>
      <div class="lg:w-4/12 lg:text-right">
          <base-button>Purchase Now</base-button>
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
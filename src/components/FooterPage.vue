<template>
  <div class="space-y-8">
    <div class="lg:flex items-center justify-between space-y-8 lg:space-y-0">
      <div class="lg:w-4/12">
        <ul class="text-sm text-grey-400">
          <li><g-link to="/about">@2020 Yourcompany</g-link></li>
        </ul>
      </div>
      <div class="lg:w-4/12">
        <g-image src="~/assets/Landie.png" class="lg:mx-auto"/>
      </div>
      <div class="lg:w-4/12 lg:text-right">
          <base-button>Purchase Now</base-button>
      </div>
    </div>
    <div class="lg:flex border-t-2 border-gray-200 pt-8 space-y-8 lg:space-y-0">
      <div class="w-6/12">
        <ul class="lg:flex text-sm text-grey-300 space-y-4 lg:space-y-0 lg:space-x-12">
          <li><g-link to="/home/">Home</g-link></li>
          <li><g-link to="/about/">About</g-link></li>
          <li><g-link to="/contact/">Contact</g-link></li>
        </ul>
      </div>
      <div class="w-6/12">
        <ul class="flex items-center text-sm text-grey-300 space-x-4 lg:space-x-12 lg:justify-end">
          <li><g-link to="/Facebook/"><g-image src="~/assets/Facebook.png" /></g-link></li>
          <li><g-link to="/Linkedin/"><g-image src="~/assets/Linkedin.png" /></g-link></li>
          <li><g-link to="/Twitter/"><g-image src="~/assets/Twitter.png" /></g-link></li>
          <li><g-link to="/Youtube/"><g-image src="~/assets/Youtube.png" /></g-link></li>
          <li><g-link to="/Instagram/"><g-image src="~/assets/Instagram.png" /></g-link></li>
        </ul>
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
<template>
  <div class="absolute inset-x-0 top-0">
    <div
      class="
        px-5
        lg:px-40
        container
        mx-auto
        hidden
        lg:flex
        lg:items-center
        justify-between
        lg:py-8
        space-y-8
        lg:space-y-0
        
      "
    >
      <div class="lg:w-4/12">
        <ul
          class="
            lg:flex
            text-sm text-blue-600
            space-y-4
            lg:space-y-0 lg:space-x-12
          "
        >
          <li><g-link to="/home/">Home</g-link></li>
          <li><g-link to="/about/">About</g-link></li>
          <li><g-link to="/contact/">Contact</g-link></li>
        </ul>
      </div>
      <div class="lg:w-4/12">
        <g-image src="~/assets/Landie.png" class="lg:mx-auto" />
      </div>
      <div class="lg:w-4/12 lg:text-right">
        <base-button>Buy Now</base-button>
      </div>
    </div>
    <div class="lg:hidden px-5 text-right">
      <button @click="ToggleMenu" class="mt-4 w-12 relative z-20">
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="bars"
          class="svg-inline--fa fa-bars fa-w-14"
          :class="{
          'text-blue-300': MenuActive === false,
          'text-blue-900': MenuActive === true,
        }"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        ><!--:class qui invece per gestire al click il colore dell'hamburger -->
          {{ MenuActive }}
          <path
            fill="currentColor"
            d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"
          ></path>
        </svg>
      </button>
      <div
        class="
          fixed
          inset-0
          bg-blue-500
          w-full
          h-full
          transform
          transition-all
          duration-300
          p-4
        "
        :class="{
          '-translate-x-full': MenuActive === false,
          'translate-x-0': MenuActive === true,
        }"
      ><!-- :class inserito qui per creare l'effetto transazione per l'hamburger -->
        <div class="lg:w-4/12">
          <g-image src="~/assets/Landie.png" class="lg:mx-auto" />
        </div>
        <div class="lg:w-4/12 text-left">
          <ul
            class="
              lg:flex
              text-sm text-blue-600
              space-y-4
              lg:space-y-0 lg:space-x-12
              mb-4
            "
          >
            <li><g-link to="/home/">Home</g-link></li>
            <li><g-link to="/about/">About</g-link></li>
            <li><g-link to="/contact/">Contact</g-link></li>
          </ul>
        </div>
        <div class="lg:w-4/12 text-left lg:text-right">
          <base-button>Buy Now</base-button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BaseButton from "~/components/BaseButton.vue";

export default {
  components: {
    BaseButton,
  },
  data: () => ({
    MenuActive: false,
  }),
  methods: {
    ToggleMenu() {
      this.MenuActive = !this.MenuActive
    },
  },
};
</script>

<style>
</style>


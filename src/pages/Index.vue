<template>
  <div class="relative">
    <navbar class="z-30" />
    <div class="lg:py-56 relative">
      <app-container class="flex flex-col-reverse lg:block">
        <div class="lg:w-6/12 relative z-10">
          <div class="space-y-2 lg:space-y-8">
            <h1 class="text-5xl text-blue-900 font-medium">
              Introduce Yuor Product Quickly & Effectively
            </h1>
            <div class="text-blue-600 space-y-6">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Adipisci assumenda veritatis fuga, illo a blanditiis quod sunt!
                Animi numquam, adipisci quasi obcaecati impedit, dolorem vitae
                amet non, tempore libero voluptatibus!
              </p>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Necessitatibus rem rerum perspiciatis accusantium corrupti optio
                minima asperiores
              </p>
            </div>
            <div class="space-x-4">
              <base-button>
                Purchase UI Kit
              </base-button>
              <button
                class="text-blue-900 bg-white border-blue-900 border px-8"
              >
                Learn More
              </button>
            </div>
          </div>
        </div>
        <g-image
          class="
            lg:absolute
            lg:w-8/12
            top-0
            right-0
            bottom-0
            object-cover
            h-full
          "
          src="~/assets/img-background.png"
        />
      </app-container>
    </div>
    <div>
      <app-container class="lg:flex my-24 lg:my-36 lg:space-x-4">
        <div class="lg:w-6/12 lg:flex lg:flex-col lg:justify-center">
          <text-color>
            <template v-slot:title>
              <h2>
                Light, Fast & Powerful
              </h2>
            </template>
          </text-color> 
          <text-color class="lg:space-y-8">
            <template v-slot:text> 
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci
                assumenda veritatis fuga, illo a blanditiis quod sunt! Animi
                numquam, adipisci quasi obcaecati impedit, dolorem vitae amet non,
                tempore libero voluptatibus!
              </p>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Necessitatibus rem rerum perspiciatis accusantium corrupti optio
                minima asperiores
              </p>
            </template>
          </text-color>
          <div class="flex lg:space-x-8 lg:my-12">
            <div class="space-y-4">
              <g-image src="~/assets/Line.png" />
              <h3 class="text-blue-900 font-medium">Title Goes Here</h3>
              <p class="text-xs text-grey-600">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Pariatur, alias obcaecati.</p>
            </div>
            <div class="space-y-4">
              <g-image src="~/assets/Line.png" />
              <h3 class="text-blue-900 font-medium">Title Goes Here</h3>
              <p class="text-xs text-grey-600">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Pariatur, alias obcaecati.</p>
            </div>
          </div>
        </div>
        <div class="lg:w-6/12">
          <g-image src="~/assets/mobile.png"/>
        </div>
      </app-container>
    </div>
    <app-container class="space-y-12 lg:space-y-40">
      <div class="flex">
        <div class="w-6/12">
          <g-image src="~/assets/main_img1.png"/>
        </div>
        <div class="w-6/12 lg:flex lg:flex-col lg:justify-center">
          <text-color>
            <template v-slot:title>
              <h2>
                Light, Fast & Powerful
              </h2>
            </template>
          </text-color> 
          <text-color class="lg:space-y-8">
            <template v-slot:text> 
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci
                assumenda veritatis fuga, illo a blanditiis quod sunt! Animi
                numquam, adipisci quasi obcaecati impedit, dolorem vitae amet non,
                tempore libero voluptatibus!
              </p>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Necessitatibus rem rerum perspiciatis accusantium corrupti optio
                minima asperiores
              </p>
            </template>
          </text-color>
        </div>
      </div>
      <div class="flex">
        <div class="w-6/12">
          <g-image src="~/assets/main_img2.png"/>
        </div>
        <div class="w-6/12 lg:flex lg:flex-col lg:justify-center">
          <text-color>
            <template v-slot:title>
              <h2>
                Light, Fast & Powerful
              </h2>
            </template>
          </text-color> 
          <text-color class="lg:space-y-8">
            <template v-slot:text> 
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci
                assumenda veritatis fuga, illo a blanditiis quod sunt! Animi
                numquam, adipisci quasi obcaecati impedit, dolorem vitae amet non,
                tempore libero voluptatibus!
              </p>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Necessitatibus rem rerum perspiciatis accusantium corrupti optio
                minima asperiores
              </p>
            </template>
          </text-color>
        </div>
      </div>
      <div class="flex">
        <div class="w-6/12">
          <g-image src="~/assets/main_img3.png"/>
        </div>
        <div class="w-6/12 lg:flex lg:flex-col lg:justify-center">
          <text-color>
            <template v-slot:title>
              <h2>
                Light, Fast & Powerful
              </h2>
            </template>
          </text-color> 
          <text-color class="lg:space-y-8">
            <template v-slot:text> 
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci
                assumenda veritatis fuga, illo a blanditiis quod sunt! Animi
                numquam, adipisci quasi obcaecati impedit, dolorem vitae amet non,
                tempore libero voluptatibus!
              </p>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Necessitatibus rem rerum perspiciatis accusantium corrupti optio
                minima asperiores
              </p>
            </template>
          </text-color>
          <div class="lg:my-8">
            <base-button>Purchase Now</base-button>
          </div>
        </div>
      </div>
    </app-container>
  </div>
</template>


<script>
import navbar from "~/components/navbar.vue";
import AppContainer from "~/components/AppContainer.vue";
import BaseButton from "~/components/BaseButton.vue";
import TextColor from "~/components/TextColor.vue";

export default {
  components: {
    navbar,
    AppContainer,
    BaseButton,
    TextColor
  },
};
</script>





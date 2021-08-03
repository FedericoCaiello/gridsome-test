<template>
  <div class="relative">
    <navbar class="z-30" />
    <div class="py-20 lg:py-56 relative">
      <app-container class="flex flex-col-reverse lg:block">
        <div class="lg:w-6/12 relative z-10">
          <div class="space-y-2 lg:space-y-8">
            <h1 class="text-5xl text-blue-900 font-medium">
              Introduce Yuor Product Quickly & Effectively
            </h1>
            <text-color>
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
            </text-color>
            <div class="space-x-4">
              <base-button class="bg-blue-700 text-white px-8">
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
      <app-container class="lg:flex lg:my-36 lg:space-x-4">
        <div class="lg:w-6/12 lg:space-y-12 lg:flex lg:flex-col lg:justify-center">
          <h2 class="text-blue-900 text-4xl font-medium">
            Light, Fast & Powerful
          </h2>
          <text-color>
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
          </text-color>
          <div class="flex lg:space-x-8">
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
    TextColor,
  },
};
</script>





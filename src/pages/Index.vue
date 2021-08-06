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
              <base-button> Purchase UI Kit </base-button>
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
        <div class="lg:w-6/12">
          <div class="text-blue-900 text-4xl font-medium">
            <h2 class="mb-4">Light, Fast & Powerful</h2>
          </div>
          <div class="text-blue-600">
            <p class="mb-4">
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
          </div>
          <div class="flex lg:space-x-8 lg:my-12">
            <div class="space-y-4">
              <g-image src="~/assets/Line.png" />
              <h3 class="text-blue-900 font-medium">Title Goes Here</h3>
              <p class="text-xs text-grey-600">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Pariatur, alias obcaecati.
              </p>
            </div>
            <div class="space-y-4">
              <g-image src="~/assets/Line.png" />
              <h3 class="text-blue-900 font-medium">Title Goes Here</h3>
              <p class="text-xs text-grey-600">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Pariatur, alias obcaecati.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-6/12">
          <g-image src="~/assets/mobile.png" />
        </div>
      </app-container>
    </div>
    <app-container class="space-y-12 lg:space-y-40">
      <card-highligth>
        <template v-slot:image>
          <g-image src="~/assets/main_img1.png" />
        </template>
        <template v-slot:title> Light, Fast & Powerful </template>
        <template v-slot:text>
          <div class="text-blue-600">
            <p class="mb-4">
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
          </div>
        </template>
      </card-highligth>
      <card-highligth>
        <template v-slot:image>
          <g-image src="~/assets/main_img2.png" />
        </template>
        <template v-slot:title> Light, Fast & Powerful </template>
        <template v-slot:text>
          <div class="text-blue-600">
            <p class="mb-4">
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
          </div>
        </template>
      </card-highligth>
      <card-highligth>
        <template v-slot:image>
          <g-image src="~/assets/main_img3.png" />
        </template>
        <template v-slot:title> Light, Fast & Powerful </template>
        <template v-slot:text>
          <div class="text-blue-600">
            <p class="mb-4">
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
          </div>
          <base-button class="mt-4">Purchase Now</base-button>
        </template>
      </card-highligth>
    </app-container>
    <div class="bg-blue">
      <app-container class="flex justify-center">
        <!-- lo sfondo deve coprire tutto la base -->
        <div class="w-7/12 text-center py-64">
          <h2 class="text-4xl font-medium">A Price To Suite Everyone</h2>
          <p class="text-blue-600 my-4">
            Corrupti quia temporibus nesciunt, quos, ipsum eum eius, nulla
            voluptate corporis aspernatur iusto unde fugit laborum mollitia ipsa
            veniam inventore rerum qui.
          </p>
          <div>
            <p class="font-medium text-5xl text-blue-700">$ 40</p>
            <p class="text-blue-600 mt-4">UI Design Kit</p>
          </div>
          <div class="my-12">
            <p class="text-grey-600 text-sm">See, One time. Simple.</p>
            <base-button class="mt-2">Purchase Now</base-button>
          </div>
        </div>
      </app-container>
    </div>
    <div class="bg-blue-500 py-8">
      <app-container>
        <app-footer />
      </app-container>
    </div>
    
  </div>
</template>


<script>
import navbar from "~/components/navbar.vue";
import AppContainer from "~/components/AppContainer.vue";
import BaseButton from "~/components/BaseButton.vue";
import CardHighligth from "~/components/CardHighligth.vue";
import AppFooter from "~/components/AppFooter.vue";

export default {
  components: {
    navbar,
    AppContainer,
    BaseButton,
    CardHighligth,
    AppFooter,
  },
};
</script>
<style>
.bg-blue {
  width: 100%;
  background-image: url("../assets/Rectangle.png");
  background-size: cover;
}
</style>





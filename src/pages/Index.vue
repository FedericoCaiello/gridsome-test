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
            <h2>Light, Fast & Powerful</h2>
          </div>
          <div class="text-blue-600 space-y-6">
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
        <template v-slot:title>
          Light, Fast & Powerful
        </template>
        <template v-slot:text>
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
        </template>
      </card-highligth>
      <card-highligth>
        <template v-slot:image>
          <g-image src="~/assets/main_img2.png" />
        </template>
        <template v-slot:title>
          <h2>Light, Fast & Powerful</h2>
        </template>
        <template v-slot:text>
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
        </template>
      </card-highligth>
      <card-highligth>
        <template v-slot:image>
          <g-image src="~/assets/main_img3.png" />
        </template>
        <template v-slot:title>
          <h2>Light, Fast & Powerful</h2>
        </template>
        <template v-slot:text>
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
        </template>
      </card-highligth>
    </app-container>
    <app-container class="mt-24 relative">
      <g-image src="~/assets/Rectangle.png" />
      <div class="absolute top-1/4 left-1/3 text-center">
        <h2>A Price To Suite Everyone</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corrupti
          quia temporibus nesciunt, quos, ipsum eum eius, nulla voluptate
          corporis aspernatur iusto unde fugit laborum mollitia ipsa veniam
          inventore rerum qui.
        </p>
      </div>
    </app-container>
  </div>
</template>


<script>
import navbar from "~/components/navbar.vue";
import AppContainer from "~/components/AppContainer.vue";
import BaseButton from "~/components/BaseButton.vue";
import CardHighligth from "~/components/CardHighligth.vue";

export default {
  components: {
    navbar,
    AppContainer,
    BaseButton,
    CardHighligth,
  },
};
</script>




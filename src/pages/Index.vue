<template>
  <div class="relative">
    <navbar class="z-30" />
    <div class="py-56 relative">
      <app-container
        class="flex flex-col-reverse lg:block"
      >  
        <div class="lg:w-6/12 relative z-10">
          <div class="space-y-8">
            <h1 class="text-5xl text-blue-900 font-medium">
              Introduce Yuor Product Quickly & Effectively
            </h1>
            <div class="text-lg text-blue-600 space-y-6">
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
      <app-container>
        <div class="w-6/12">
          <h2>Light, Fast & Powerful</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Dignissimos eos dolor nisi nostrum fuga! Natus omnis commodi, nulla
            necessitatibus vel sint sed eos, culpa, excepturi ipsam id
            voluptates iure minus.
          </p>
          <p>
            Perferendis, asperiores. Necessitatibus odio porro suscipit
            inventore facere magnam earum ea eos voluptates assumenda recusandae
            cumque repellendus esse laboriosam, voluptatibus, totam dolorem!
          </p>
        </div>
        <div class="w-6/12"></div>
      </app-container>
    </div>
  </div>
</template>


<script>
import navbar from "~/components/navbar.vue";
import AppContainer from "~/components/AppContainer.vue";
import BaseButton from "~/components/BaseButton.vue"

export default {
  components: {
    navbar,
    AppContainer,
    BaseButton
  },
};
</script>





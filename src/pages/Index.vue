<template>
  <div class="py-56 relative">
    <div class="px-5 lg:px-40 container mx-auto flex flex-col-reverse lg:block">
      <navbar class="z-30" />
      <div class="lg:w-6/12">
        <div class="text-left space-y-6">
            <h1 class="text-5xl text-blue-900 font-medium font-sans">Introduce Yuor Product Quickly & Effectively</h1>
            <div class="text-lg text-blue-600 space-y-6">
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci assumenda veritatis fuga, illo a blanditiis quod sunt! Animi numquam, 
              adipisci quasi obcaecati impedit, dolorem vitae amet non, tempore libero voluptatibus!</p>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Necessitatibus rem rerum perspiciatis accusantium corrupti optio minima asperiores</p>
            </div>
        </div>
      
      </div>
      <div class="lg:w-8/12">
        <g-image class="lg:absolute top-0 right-0 bottom-0 object-cover" src="~/assets/img-background.png" width="" />
      </div>
    </div>
  </div>
</template>


<script>
import navbar from "~/components/navbar.vue";

export default {
  components: {
    navbar,
  },
};
</script>





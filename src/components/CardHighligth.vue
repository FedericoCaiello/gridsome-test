<template>
  <div class="lg:flex items-center">
    <!-- parte mobile -->
    <div class="lg:w-6/12">
      <slot name="image" />
    </div>
    <div class="lg:w-6/12">
      <div>
        <h2 class="text-blue-900 text-4xl font-medium mb-4">
          <slot name="title" />
        </h2>
      </div>
      <div>
        <slot name="text" />
      </div>
    </div>
  </div>
</template>
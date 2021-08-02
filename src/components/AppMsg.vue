<template>
  <div>
    {{ messaggio }}
  </div>
</template>

<script>
export default {
  props: {
    messaggio: {
      type: String,
      required: true,
    },
  },
};
</script>

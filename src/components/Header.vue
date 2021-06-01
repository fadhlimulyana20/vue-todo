<template>
  <h1 class="text-2xl font-bold">{{ text }}</h1>
</template>

<script>
export default {
  name: "Header",
  props: {
    text: {
      type: String,
      default: "Hello World",
    },
  },
};
</script>
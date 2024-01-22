<script setup>
defineProps({
  image: {
    type: String,
    required: true,
  },
  title: {
    type: String,
    required: true,
  },
  text: {
    type: String,
    required: true,
  },
});
</script>
<template>
  <div class="d-flex gap-3 align-items-center m-3">
    <img :src="image" alt="location" />
    <div class="p-2">
      <h3 class="fw-bold fs-4">{{ title }}</h3>
      <p class="fs-6 m-0">{{ text }}</p>
    </div>
  </div>
</template>

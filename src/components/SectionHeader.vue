<script setup>
import largeArrow from "../../public/largeArrow.svg";

defineProps({
  title: {
    type: String,
    required: true,
  },
  title2: {
    type: String,
    required: true,
  },
  text: {
    type: String,
    required: false,
  },
});
</script>
<template>
  <div class="d-flex justify-content-between">
    <div class="col-5">
      <h2 class="fw-bold text-uppercase" style="font-size: 36px">
        {{ title }}
      </h2>
      <div class="d-flex gap-5 align-items-center">
        <p class="fw-light text-uppercase m-0" style="font-size: 36px">
          {{ title2 }}
        </p>
        <img :src="largeArrow" alt="arrow" />
      </div>
    </div>
    <div class="col-6">
      <p>
        {{ text }}
      </p>
    </div>
  </div>
</template>

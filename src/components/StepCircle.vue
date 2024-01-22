<script setup>
import smallArrow from "../../public/smallArrow.svg";

defineProps({
  stepNumber:{
    type: String,
    required:true,
  },
  title:{
    type: String,
    required:true,
  }
})
</script>
<template>
  <div
    class="d-flex flex-column align-items-center justify-content-center gap-4"
    style="max-width: 220px;"
  >
    <div
      class="p-4 rounded-circle"
      style="
        width: 200px;
        height: 200px;
        background-color: rgba(14, 14, 14, 0.3);
      "
    >
      <div
        class="bg-primary w-100 h-100 rounded-circle d-flex justify-content-center align-items-center"
      >
        <span class="fw-bold" style="color: #343045; font-size: 60px">{{
          stepNumber
        }}</span>
      </div>
    </div>
    <div class="d-flex gap-3 align-items-start">
      <img
        :src="smallArrow"
        alt="left arrow"
        style="width: 24px; height: auto; padding-top: 4px;"
      />
      <h2 class="fw-bold m-0" style="font-size: 24px; min-height: 64px;">{{ title }}</h2>
    </div>
  </div>
</template>

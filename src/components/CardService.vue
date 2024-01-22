<script setup>
import Button from "./Button.vue";

defineProps({
  image:{
    type:String,
    required:true,
  },
  title:{
    type:String,
    required:true,
  },
  text:{
    type:String,
    required:true,
  },
})
</script>
<template>
  <div class="col">
    <div class="card h-100 bg-radial d-flex flex-column align-items-center p-4">
      <div
        class="rounded-circle position-relative overflow-hidden"
        style="
          background-color: rgba(14, 14, 14, 0.3);
          width: 220px;
          height: 220px;
        "
      >
        <img
          :src="image"
          class="position-absolute rounded-circle"
          style="width: 190px; height: 190px; top: 15px; left: 15px"
          alt="service"
        />
      </div>
      <div class="card-body d-flex flex-column align-items-center gap-3">
        <h4 class="card-title fs-4 fw-bold text-uppercase m-0">{{ title }}</h4>
        <div
          class="w-75"
          style="height: 1px; background-color: rgba(192, 183, 232, 0.3)"
        ></div>
        <p class="card-text" style="font-size: 12px">
          {{text}}
        </p>
        <Button button-text="TRY IT NOW" />
      </div>
    </div>
  </div>
</template>
<style scoped>
.bg-radial {
  background: rgb(67, 61, 96);
  background: radial-gradient(
    circle,
    rgba(67, 61, 96, 1) 0%,
    rgba(33, 30, 46, 1) 100%
  );
  border-radius: 40px;
}
</style>
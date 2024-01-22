<script setup>
import { ref } from "vue";
defineProps({
  buttonText: {
    type: String,
    required: true,
  },
  secondary: {
    type: Boolean,
  },
});
//const buttonText= ref('')
</script>
<template>
  <button
    class="button text-uppercase fw-bold"
    :class="secondary ? 'btn-transparent' : 'btn-gradiente'"
  >
    {{ buttonText }}
  </button>
</template>
<style scoped>
.button {
  padding: 16px 40px;
  border-radius: 40px;
  font-size: 12px;
  border: none;
}
.btn-gradiente {
  background: rgb(129, 118, 175);
  background: linear-gradient(
    90deg,
    rgba(129, 118, 175, 1) 0%,
    rgba(192, 183, 232, 1) 100%
  );
  color: #343045;
}
.btn-transparent {
  background-color: transparent;
  border: 2px solid white;
  color: white;
}
</style>

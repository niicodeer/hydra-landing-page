<script setup></script>

<template>
  <div class="container py-4 px-3 mx-auto">
    <h1>Hello, Bootstrap and Vite!</h1>
    <button class="btn btn-gradiente1 py-4 px-7">Primary button</button>
  </div>
</template>
<style scoped>
.btn-gradiente1 {
  background: rgb(129, 118, 175);
  background: linear-gradient(
    90deg,
    rgba(129, 118, 175, 1) 0%,
    rgba(192, 183, 232, 1) 100%
  );
}
</style>

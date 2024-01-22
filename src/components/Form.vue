<script setup>
import Button from "./Button.vue";
</script>
<template>
  <div
    class="w-100"
    style="
      height: 1000px;
      background: radial-gradient(
        circle,
        rgba(67, 61, 96, 1) 0%,
        rgba(33, 30, 46, 1) 80%
      );
      border-radius: 100px;
      padding: 90px;
    "
  >
    <div class="d-flex flex-column gap-3 align-items-center">
      <h2 class="fw-bold text-uppercase text-center" style="font-size: 36px">
        JOIN HYDRA
      </h2>
      <div class="w-25 bg-primary" style="height: 1px"></div>
      <p
        class="fw-light text-uppercase m-0 text-center"
        style="font-size: 36px"
      >
        Let’s Build Your VR Experience
      </p>
    </div>
    <form class="row">
      <div class="col-md-6">
        <input type="email" class="form-control" placeholder="First Name"/>
      </div>
      <div class="col-md-6">
        <input type="password" class="form-control" placeholder="Last Name"/>
      </div>
      <div class="col-md-6">
        <!-- <label for="inputEmail4" class="form-label">Email</label> -->
        <input type="email" class="form-control" placeholder="Email"/>
      </div>
      <div class="col-md-6">
        <input type="password" class="form-control" placeholder="Phone Number"/>
      </div>
      <div class="col-12">
        <input type="password" class="form-control" placeholder="Subject"/>
      </div>
      <div class="col-12">
        <textarea class="form-control" aria-label="With textarea" placeholder="Tell Us Something..."></textarea>
      </div>
      <div class="w-25 mx-auto" style="margin-top: 50px;">
        <Button buttonText="SEND TO HYDRA" class="w-100"/>
      </div>
    </form>
  </div>
</template>
<style scoped>
input,
textarea {
  border-radius: 40px;
  height: 72px;
  margin-top: 40px;
  border: 2px solid white;
  background-color: transparent;
  color: white;
  padding: 12px 24px;
}
input::placeholder,
textarea::placeholder{
  color:white;
}
textarea {
  height: 210px;
  resize: none;
}
</style>

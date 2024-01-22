<script setup>
import footerLogo from "../../public/footerLogo.png";
import facebook from "../../public/facebook.svg";
import twitter from "../../public/twitter.svg";
import instagram from "../../public/instagram.svg";
import linkedin from "../../public/linkedin.svg";
import youtube from "../../public/youtube.svg";
import pinterest from "../../public/pinterest.svg";
import Button from "./Button.vue";
</script>

<template>
  <footer class="d-flex flex-column align-items-center">
    <div class="w-100 row d-flex justify-content-around">
      <div class="col-2">
        <img :src="footerLogo" alt="footer" />
      </div>
      <div
        class="h-full p-0"
        style="
          width: 6px;
          background: linear-gradient(
            0deg,
            rgba(52, 48, 69, 1) 0%,
            rgba(192, 183, 232, 1) 33%,
            rgba(129, 118, 175, 1) 66%,
            rgba(52, 48, 69, 1) 100%
          );
        "
      ></div>
      <div class="col-2 d-flex flex-column">
        <a href="">ABOUT</a>
        <a href="">SERVICES</a>
        <a href="">TECHNOLOGIES</a>
        <a href="">HOW TO</a>
        <a href="">JOIN HYDRA</a>
      </div>
      <div
        class="h-full p-0"
        style="
          width: 6px;
          background: linear-gradient(
            0deg,
            rgba(52, 48, 69, 1) 0%,
            rgba(192, 183, 232, 1) 33%,
            rgba(129, 118, 175, 1) 66%,
            rgba(52, 48, 69, 1) 100%
          );
        "
      ></div>
      <div class="col-2 d-flex flex-column">
        <a href="">F.A.Q.</a>
        <a href="">SITEMAP</a>
        <a href="">CONDITIONS</a>
        <a href="">LICENSES</a>
      </div>
      <div
        class="h-full p-0"
        style="
          width: 6px;
          background: linear-gradient(
            0deg,
            rgba(52, 48, 69, 1) 0%,
            rgba(192, 183, 232, 1) 33%,
            rgba(129, 118, 175, 1) 66%,
            rgba(52, 48, 69, 1) 100%
          );
        "
      ></div>
      <div class="col-3 d-flex flex-column gap-4">
        <p class="fw-bold">SOCIALIZE WITH HYDRA</p>
        <div class="d-flex gap-3">
          <a href="#"><img :src="facebook" alt="facebook" /></a>
          <a href="#"><img :src="twitter" alt="twitter" /></a>
          <a href="#"><img :src="linkedin" alt="linkedin" /></a>
          <a href="#"><img :src="youtube" alt="youtube" /></a>
          <a href="#"><img :src="instagram" alt="instagram" /></a>
          <a href="#"><img :src="pinterest" alt="pinterest" /></a>
        </div>
        <Button buttonText="BUILD YOUR WORLD" />
      </div>
    </div>
    <div
        class="w-100 p-0 my-5"
        style="
          height: 2px;
          background: linear-gradient(
            90deg,
            rgba(52, 48, 69, 1) 0%,
            rgba(192, 183, 232, 1) 33%,
            rgba(129, 118, 175, 1) 66%,
            rgba(52, 48, 69, 1) 100%
          );
        "
      ></div>
      <div>
        <p style="font-size: 14px;">2023 © HYDRA LANDING PAGE - DESIGNED BY ZINE. E. FALOUTI | DEVELOPED BY NICO RADIN - ALL RIGHTS RESERVED </p>
      </div>
  </footer>
</template>
<style scoped>
a {
  color: white;
  font-weight: bold;
  text-decoration: none;
  margin-bottom: 20px;
}
</style>

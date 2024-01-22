<script setup>
import image1 from "../../public/image1.png";
import smallArrow from "../../public/smallArrow.svg";
import Button from "./Button.vue";
import ContactBanner from "./ContactBanner.vue";
</script>
<template>
  <section>
    <div class="d-flex justify-content-between align-items-center">
      <div class="col-4">
        <h1 class="fw-bold">
          <span class="text-gradient1 fw-bold">Dive</span> Into The Depths
          <br />Of
          <span class="text-gradient2 fw-bold">Virtual Reality</span>
        </h1>
        <p class="d-md-block d-none">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore nisl tincidunt eget.
          Lectus mauris eros in vitae .
        </p>
        <div class="d-flex gap-5 justify-content-start">
          <Button buttonText="BUILD YOUR WORLD" />
          <img :src="smallArrow" />
        </div>
      </div>
      <div class="col-5">
        <div class="rectangle position-relative">
          <div class="rectangle2 position-absolute bg-primary overflow-hidden">
            <img :src="image1" />
          </div>
        </div>
      </div>
    </div>
    <ContactBanner />
  </section>
</template>
<style scoped>
section {
  margin: 5rem 0;
}
section > div {
  margin-bottom: 80px;
}
h1 {
  margin-bottom: 36px;
  line-height: 56px;
}
span {
  font-size: 46px;
}
p {
  margin-bottom: 64px;
}
.text-gradient1 {
  background: -webkit-linear-gradient(to right, #c0b7e8, #8176af);
  background: linear-gradient(to right, #c0b7e8, #8176af);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.text-gradient2 {
  background: -webkit-linear-gradient(to right, #8176af, #c0b7e8);
  background: linear-gradient(to right, #8176af, #c0b7e8);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.rectangle {
  background-color: rgba(0, 0, 0, 0.13);
  width: 524px;
  height: 455px;
  border-radius: 100px;
  border-bottom-left-radius: 240px;
}
.rectangle2 {
  background-color: rgba(0, 0, 0, 0.15);
  top: 15px;
  left: 17px;
  width: 490px;
  height: 425px;
  border-radius: 100px;
  border-bottom-left-radius: 240px;
}
</style>

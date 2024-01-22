<script setup>
import SectionHeader from "./SectionHeader.vue";
import Button from "./Button.vue";
import image2 from '../../public/image2.png'
</script>
<template>
  <section>
    <SectionHeader
      title="Introduction"
      title2="To Hydra vr"
      text="Vitae sapien pellentesque habitant morbi tristique senectus et netus et.
        Feugiat nibh sed pulvinar proin gravida hendrerit lectus. Mi sit amet
        mauris commodo quis imperdiet massa tincidunt nunc. Viverra aliquet eget
        sit amet tellus. Ornare lectus sit amet est placerat in. Lectus magna
        fringilla urna porttitor rhoncus vitae."
    />
    <div class="d-flex justify-content-between align-items-center my-5">
      <div class="col-4 rectangle overflow-hidden">
        <img :src="image2" alt="image">
      </div>
      <div class="col-6 ">
        <h2 class="fw-bold text-uppercase" style="font-size: 36px">ABOUT</h2>
        <p class="fw-light text-uppercase mb-5" style="font-size: 36px">
          HYDRA VR
        </p>
        <p class="mb-4">
          Eget mi proin sed libero enim sed faucibus turpis. Nisl rhoncus mattis
          rhoncus urna neque viverra justo. Vivamus at augue eget arcu dictum.
          Ultrices gravida dictum fusce ut placerat orci. Aenean et tortor at
          risus viverra adipiscing at in. Mattis aliquam faucibus purus in
          massa. Est placerat in egestas erat imperdiet sed. Consequat semper
          viverra nam libero justo laoreet sit amet. Aliquam etiam erat velit
          scelerisque in dictum non consectetur a. Laoreet sit amet cursus sit
          amet. Vel eros donec ac odio tempor orci dapibus. Sem nulla pha retra
          diam sit amet nisl suscipit adipiscing bibendum. Leo a diam
          sollicitudi n tempor.
        </p>
        <Button button-text="LET’S GET IN TOUCH"/>
      </div>
    </div>
  </section>
</template>
<style scoped>

.rectangle {
  background-color: rgba(0, 0, 0, 0.13);
  width: 524px;
  height: 555px;
  border-radius: 100px;
  border-top-left-radius: 240px;
  border-bottom-right-radius: 240px;
}
</style>

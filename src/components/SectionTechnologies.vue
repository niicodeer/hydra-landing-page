<script setup>
import image3 from "../../public/image3.png";
import tech1 from "../../public/Hydra-Tech1.png";
import tech2 from "../../public/Hydra-Tech2.png";
import tech3 from "../../public/Hydra-Tech3.png";
import tech4 from "../../public/Hydra-Tech4.png";

</script>
<template>
  <section>
    <div
      class="w-100 rounded-pill bg-primary position-relative d-flex justify-content-center align-items-center z-1"
      style="height: 300px"
    >
    <!-- image -->
      <div
        class="position-absolute w-100 h-100 top-0 left-0 bg-secondary overflow-hidden d-block rounded-pill"
      >
        <img
          :src="image3"
          alt="image"
          class="d-block w-100 h-auto opacity-25"
        />
      </div>
      <div class="z-2">
        <h2 class="fw-bold text-uppercase text-center" style="font-size: 36px">
          TECHNOLOGIES & HARDWARE
        </h2>
        <p
          class="fw-light text-uppercase m-0 text-center"
          style="font-size: 36px"
        >
          USED BY HYDRA VR.
        </p>
      </div>
      <!-- arrow -->
      <div
        class="rounded-circle position-absolute z-2 top-100 start-50 translate-middle p-3"
        style="
          width: 100px;
          height: 100px;
          background-color: rgba(14, 14, 14, 0.32);
        "
      >
        <div
          class="w-100 h-100 bg-primary rounded-circle d-flex justify-content-center align-items-center"
        >
          <div
            style="
              width: 20px;
              height: 20px;
              border: 3px solid #433d60;
              transform: rotate(45deg);
              border-top: none;
              border-left: none;
            "
          ></div>
        </div>
      </div>
    </div>
    <!-- companies images -->
    <div class="row row-cols-4 justify-content-around align-items-center my-5">
      <img :src="tech1" alt="tech1" style="max-width: 174px; max-height: 174px;">
      <img :src="tech2" alt="tech1" style="max-width: 250px; max-height: 250px;">
      <img :src="tech3" alt="tech1" style="max-width: 250px; max-height: 250px;">
      <img :src="tech4" alt="tech1" style="max-width: 250px; max-height: 250px;">
    </div>
  </section>
</template>

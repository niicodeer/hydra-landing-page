<script setup>
import SectionHeader from "./SectionHeader.vue";
import CardService from "./CardService.vue";

import simulation from "../../public/simulation.png";
import education from "../../public/education.png";
import selfcare from "../../public/selfcare.png";
import outdoor from "../../public/outdoor.png";
</script>
<template>
  <section>
    <SectionHeader
      title="WHY BUILD"
      title2="WITH HYDRA?"
      text="Vitae sapien pellentesque habitant morbi tristique senectus et netus et. Feugiat nibh sed pulvinar proin gravida hendrerit lectus. Mi sit amet mauris commodo quis imperdiet massa tincidunt nunc. Viverra aliquet eget sit amet tellus. Ornare lectus sit amet est placerat in. Lectus magna fringilla urna porttitor rhoncus vitae."
    />
    <div class="row row-cols-1 row-cols-md-4 g-4" style="margin: 100px 0">
      <CardService
        :image="simulation"
        title="SIMULATION"
        text="Vitae sapien pellentesque habitant morbi nunc. Viverra aliquet  porttitor rhoncus libero justo laoreet sit amet vitae."
      />
      <CardService
        :image="education"
        title="EDUCATION"
        text="Vitae sapien pellentesque habitant morbi nunc. Viverra aliquet  porttitor rhoncus libero justo laoreet sit amet vitae."
      />
      <CardService
        :image="selfcare"
        title="SELF-CARE"
        text="Vitae sapien pellentesque habitant morbi nunc. Viverra aliquet  porttitor rhoncus libero justo laoreet sit amet vitae."
      />
      <CardService
        :image="outdoor"
        title="OUTDOOR"
        text="Vitae sapien pellentesque habitant morbi nunc. Viverra aliquet  porttitor rhoncus libero justo laoreet sit amet vitae."
      />
    </div>
  </section>
</template>
<style scoped></style>

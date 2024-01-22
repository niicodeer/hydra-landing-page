<script setup>
import SectionHeader from "./SectionHeader.vue";
import StepCircle from "./StepCircle.vue";
import Form from "./Form.vue";
</script>
<template>
  <section>
    <SectionHeader
      title="HOW WE BUILD"
      title2="WITH HYDRA VR?"
      text="Vitae sapien pellentesque habitant morbi tristique senectus et netus et. Feugiat nibh sed pulvinar proin gravida hendrerit lectus. Mi sit amet mauris commodo quis imperdiet massa tincidunt nunc. Viverra aliquet eget sit amet tellus. Ornare lectus sit amet est placerat in. Lectus magna fringilla urna porttitor rhoncus vitae."
    />
    <div style="margin: 100px 0">
      <div class="row-cols-4 d-flex justify-content-around">
        <StepCircle stepNumber="01" title="3D Conception & Design" />
        <StepCircle stepNumber="02" title="Interaction Design" />
        <StepCircle stepNumber="03" title="VR World User Testing" />
        <StepCircle stepNumber="04" title="Hydra VR Deploy" />
      </div>
    </div>
    <Form />
    
  </section>
</template>

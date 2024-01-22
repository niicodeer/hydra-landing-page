<script setup>
import ContactBannerItem from "./ContactBannerItem.vue";
import location from "../../public/location.svg";
import phone from "../../public/phone-call.svg";
import mail from "../../public/mail.svg";
</script>
<template>
  <div
    class="bg-radial rounded-pill w-100 p-4 d-flex justify-content-evenly h-100"
  >
    <ContactBannerItem
      :image="location"
      title="Pay Us a Visit"
      text="Union St, Seattle, WA 98101, United States"
    />
    <div class="h-auto stick"></div>
    <ContactBannerItem
      :image="phone"
      title="Give Us a Call"
      text="(110) 1111-1010"
    />
    <div class="h-auto stick"></div>
    <ContactBannerItem
      :image="mail"
      title="Send Us a Message"
      text="Contact@HydraVTech.com"
    />
  </div>
</template>

<style scoped>
.bg-radial {
  background: rgb(58, 52, 86);
  background: radial-gradient(
    circle,
    rgba(58, 52, 86, 0.95) 0%,
    rgba(33, 30, 46, 1) 100%
  );
  /* border-radius: 90px; */
}

.stick {
  width: 1px;
  background-color: rgba(192, 183, 232, 0.3);
}
</style>

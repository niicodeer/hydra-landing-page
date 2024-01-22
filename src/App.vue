<script setup>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
import SectionAbout from "./components/SectionAbout.vue";
import SectionServices from "./components/SectionServices.vue";
import SectionTechnologies from "./components/SectionTechnologies.vue";
import SectionHowTo from "./components/SectionHowTo.vue";

import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="container py-4 px-3 mx-auto">
    <Navbar />
    <HeroSection />
    <SectionAbout />
    <SectionServices />
    <SectionTechnologies />
    <SectionHowTo />
    <Footer />
  </div>
</template>


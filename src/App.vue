<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HeaderMobile from './components/HeaderMobile.vue'
import HeroSection from './components/HeroSection.vue'
import ImageTextSection from './components/ImageTextSection.vue'
import TextSection from './components/TextSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import SomeSection from './components/SomeSection.vue'
import ProjectsSection from './components/ProjectsSection.vue'
</script>

<template>
  <HeaderMobile />
  <HeroSection />
  <ImageTextSection />
  <TextSection />
  <ServicesSection />
  <SomeSection />
  <ProjectsSection />
</template>

<style scoped></style>

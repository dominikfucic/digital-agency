<script setup lang="ts">
import DotsGraphics from './DotsGraphics.vue'
</script>

<template>
  <section class="image-text-section">
    <p class="image-text-section__description">
      Lorem Ipsum is simply dummy text of the printing and typesetting industry.
    </p>
    <div class="image-text-section__content">
      <img src="../assets/office.png" />
      <DotsGraphics />
    </div>
  </section>
</template>

<style scoped>
.image-text-section__content {
  position: relative;
  top: 1.5rem;
}

.image-text-section__description {
  margin: 3rem 2.5rem;
  font-weight: 600;
  text-align: center;
}
.image-text-section__content img {
  z-index: 100;
  top: -1.5rem;
}

.image-text-section__content svg {
  position: absolute;
  z-index: -1;
  top: -1.5rem;
  left: 16rem;
}
</style>

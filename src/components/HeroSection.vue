<script setup lang="ts">
import WaveArt from './WaveArt.vue'
</script>

<template>
  <section class="hero">
    <div class="content">
      <h2>Digital Marketing</h2>
      <h1>Work that we produce for our clients</h1>
      <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard.
      </p>
      <button class="hero__content__button">Get more details</button>
    </div>
    <WaveArt />
  </section>
</template>

<style scoped>
h2 {
  color: #e87d0e;
  font-size: 1rem;
  font-style: normal;
  font-weight: 700;
  margin-bottom: 1.95rem;
}

h1 {
  color: #000;
  font-size: 2.125rem;
  font-style: normal;
  font-weight: 700;
  margin-bottom: 1.75rem;
}

.content p {
  color: #000;
  font-size: 0.875rem;
  font-style: normal;
  font-weight: 500;
  margin-bottom: 3rem;
}

.hero__content__button {
  width: 10.5rem;
  height: 2.85rem;
  border-radius: 2.5rem;
  background: linear-gradient(113deg, #fa8305 0%, #fb9e3c 100%);
  border: 0;
  color: white;
  font-weight: 500;
}

.content {
  padding: 0 3.15rem;
  padding-top: 11rem;
}

.hero {
  position: relative;
  margin-bottom: -3.5rem;
}
</style>

<script setup lang="ts">
import ForwardIcon from './icons/ForwardIcon.vue'
import BackIcon from './icons/BackIcon.vue'
</script>

<template>
  <section class="some-section">
    <h1 class="some-section__title">Lorem Ipsum</h1>
    <p class="some-section__description">
      Lorem Ipsum is simply dummy text of the printing and typesetting industry.
    </p>
    <div class="some-section__content">
      <div class="some-section__content__badge">Lorem ipsum</div>
      <h1 class="some-section__content__title">Lorem Ipsum</h1>
      <p class="some-section__content__description">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s,
      </p>
      <div class="some-section__content__button-container">
        <button class="some-section__content__button">Read more</button>
        <ArrowIcon />
      </div>
    </div>
    <div class="some-section__button-container">
      <BackIcon />
      <ForwardIcon />
    </div>
  </section>
</template>

<style scoped>
.some-section {
  background-color: #f5f5f5;
  margin-top: 6.7rem;
  padding: 3.44rem 2.5rem;
}

.some-section__title {
  font-weight: 600;
  font-size: 1.5rem;
  color: #222;
  margin-bottom: 2rem;
}

.some-section__description {
  font-weight: 400;
  color: #525252;
  margin-bottom: 2rem;
}

.some-section__content {
  background-color: #fff;
  border-radius: 1.25rem;
  display: flex;
  flex-direction: column;
  padding: 1.75rem;
}

.some-section__content div:last-child {
  justify-content: end;
}

.some-section__content__badge {
  background-color: rgba(12, 190, 100, 0.15);
  width: fit-content;
  border-radius: 0.5rem;
  padding: 0.35rem 0.7rem;
  color: #0cbe64;
  font-size: 0.875rem;
}

.some-section__content__title {
  font-size: 1.25rem;
  font-weight: 600;
}
.some-section__content__description {
  font-size: 0.75rem;
  font-weight: 400;
  color: #525252;
}

.some-section__content__button-container svg {
  width: 12px;
}
.some-section__content__button-container {
  display: flex;
  gap: 0.57rem;
}

.some-section__content__button {
  background-color: transparent;
  border: 0;
  color: #dc7000;
  font-size: 0.875rem;
  font-weight: 500;
}

.some-section div:last-child {
  justify-content: end;
}
.some-section__button-container {
  display: flex;
  margin-top: 2.87rem;
  gap: 1.5rem;
}
.some-section__button-container svg {
  border: 0;
  border-radius: 2.5rem;
  background-color: #fff;
  padding: 0.79rem;
}
</style>

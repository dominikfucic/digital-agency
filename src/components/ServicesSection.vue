<script setup lang="ts">
import MobileIcon from './icons/MobileIcon.vue'
import PCIcon from './icons/PCIcon.vue'
import VRIcon from './icons/VRIcon.vue'
import PS4Icon from './icons/PS4Icon.vue'
import ArrowIcon from './icons/ArrowIcon.vue'
</script>

<template>
  <section class="services">
    <div class="service">
      <MobileIcon />
      <h3>Mobile Game Development</h3>
      <ArrowIcon />
    </div>
    <div class="service">
      <PCIcon />
      <h3>PC Game Development</h3>
      <ArrowIcon />
    </div>
    <div class="service">
      <PS4Icon />
      <h3>PS4 Game Development</h3>
      <ArrowIcon />
    </div>
    <div class="service">
      <VRIcon />
      <h3>AR/VR Solutions</h3>
      <ArrowIcon />
    </div>
  </section>
</template>

<style scoped>
.services {
  display: flex;
  flex-direction: column;
  gap: 4rem;
}

.service {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.service h3 {
  font-size: 1rem;
  font-weight: 500;
  margin-top: 1.8rem;
  margin-bottom: 1.5rem;
}
</style>

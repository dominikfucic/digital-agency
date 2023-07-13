<script setup lang="ts">
import MenuIcon from './icons/MenuIcon.vue'
</script>

<template>
  <header>
    <h1>LOGO</h1>
    <MenuIcon />
  </header>
</template>

<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 4.375rem;
  background: linear-gradient(111deg, #e47500 0%, #df7c14 100%);
  padding: 0 1.5rem;
}

header h1 {
  color: #fff;
  font-size: 1.25rem;
  font-style: normal;
  font-weight: 700;
}
</style>

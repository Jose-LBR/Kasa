<script setup lang="ts">
import TheHeader from './components/Header.vue'
</script>

<template>
  <div class="app d-flex justify-content-center">
    <div class="app-container">
      <TheHeader />
    </div>
  </div>
</template>

<style scoped lang="scss">
.app-container {
  height: 100vh;
  width: 1440px;
  position: relative;
}
</style>

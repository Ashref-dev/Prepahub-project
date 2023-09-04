<script setup lang="ts">
import HeaderComponent from '../components/HeaderComponent.vue'
import LandingComponent from '../components/LandingComponent.vue'
</script>
<template>
  <!-- background blurry blobs -->
  <div style="width: 100%; z-index: -10" class="absolute h-screen overflow-x-hidden">
    <div
      class="absolute left-[-15%] top-[22%] h-1/3 w-1/3 rounded-full bg-[#FFC939] blur-[5em] xl:blur-[10em]"
    ></div>
    <div
      class="absolute right-[-7%] top-[5%] h-1/3 w-1/3 rounded-full bg-[#FFC939] blur-[5em] xl:blur-[10em]"
    ></div>
    <div
      class="absolute bottom-0 left-[65%] h-1/4 w-1/4 rounded-full bg-[#FFC939] blur-[6em] xl:blur-[10em]"
    ></div>
  </div>
  <!-- main content  -->
  <div class="container mx-auto">
    <HeaderComponent />
    <LandingComponent />
  </div>
</template>

<style scoped></style>

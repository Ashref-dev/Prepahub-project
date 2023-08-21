<script setup lang="ts"></script>

<template>
  <header class="flex items-center justify-between mx-8 my-4">
    <img src="../assets/logo/PrepaHub_logo_text.svg" alt="" srcset="" />

    <ul class="hidden items-center gap-4 md:flex">
      <li>Maison</li>
      <li>Calculator</li>
      <li>Aide</li>
    </ul>

    <div class="hidden gap-4 items-center justify-center md:flex">
      <p>Log in</p>
      <button style="border-radius: 35px 35px 0 35px" class="bg-black px-6 py-2 text-white rounded">
        Sign up
      </button>
    </div>
    <div class="block w-12 md:hidden">
      <img src="../assets/graphics/hamburger.svg" alt="menu" />
    </div>
  </header>
</template>

<style scoped></style>

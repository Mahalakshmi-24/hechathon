<template>
  <header class="flex gap-4 bg-black py-4">
    <TheLogo />
    <div class="flex gap-2 items-center ml-2">
      <span class="text-2xl font-semibold text-white">SEPHORA</span>
    </div>
    <TheNavBar />
  </header>
</template>


 <script setup>
import TheLogo from "./TheLogo.vue";
import TheNavBar from "./TheNavBar.vue";
</script>
<template>
  <div>
    <!-- <NuxtWelcome /> -->
    <headerPart />
    <NuxtPage />
    <footerPart />
  </div>
</template>
<script setup>
import headerPart from './components/header-part.vue';
import footerPart from './components/footer-part.vue';
</script>

<style lang="scss">
@import "public/assets/css/main.scss";
</style>
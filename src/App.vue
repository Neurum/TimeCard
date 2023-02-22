<template>
  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  scroll-padding: 5.5rem;
}
</style>

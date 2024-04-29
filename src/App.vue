<template>
  <header>

    <RouterLink to="/">Home</RouterLink>
  </header>

  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>
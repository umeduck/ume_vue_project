<script setup>
import { computed } from 'vue';
  const answer = computed(() => {
    return 321434253451 % 12132
  })
</script>
<template>
  <h1>Vue 3</h1>
  <p>1 + 1 = {{ answer }}</p>
</template>
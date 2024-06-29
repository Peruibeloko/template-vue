<script setup lang="ts">
import { ref } from 'vue';

const count = ref(0);
</script>

<template>
  <button type="button" @click="count++">count is {{ count }}</button>
</template>

<style scoped>
button {
  border: none;
  background-color: transparent;
  color: var(--fg);
  font-family: monospace;
  font-size: 2rem;
  border: 5px solid var(--red_dim);
  padding: 1rem;
  border-radius: 1rem;
  transition-duration: 200ms;
}

button:hover {
  color: var(--bg);
  background-color: var(--fg);
}
</style>

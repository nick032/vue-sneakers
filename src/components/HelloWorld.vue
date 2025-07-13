<script setup lang="ts">
import { ref } from "vue";

const count = ref(0);

function increment() {
  count.value++;
}
</script>

<template>
  <h1>{{ count }}</h1>
  <button @click="increment">Increment</button>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>

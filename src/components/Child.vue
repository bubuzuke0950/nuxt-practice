<script setup lang="ts">
defineProps<{
  message: string;
}>();
</script>

<template>
  <div class="child-component">
    <h2>Child Component</h2>
    <p>{{ message }}</p>
  </div>
</template>

<style scoped>
.child-component {
  border: solid red;
  padding: 1rem;
}
</style>

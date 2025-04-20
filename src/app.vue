<script setup lang="ts">
import Child from "./components/Child.vue";
const name = ref("Nuxt");
</script>
<template>
  <div>
    <h1>Welcome to Nuxt</h1>
    <Child :message="name" />
  </div>
</template>

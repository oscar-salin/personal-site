<script setup lang="ts">
const props = defineProps<{
  link?: string
}>();
</script>

<template>
  <a :href="link || '#'">
    <slot name="text"></slot>
  </a>
</template>

<style scoped>
a {
  display: inline-block;
  padding: 10px 20px;
  font-size: 16px;
  color: white;
  background-color: #0c8b00;
  border: none;
  border-radius: 5px;
  text-align: center;
  text-decoration: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

a:hover {
  background-color: #005c08;
}
</style>

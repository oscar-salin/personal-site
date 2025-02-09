<script setup lang="ts">
import linkButton from '../components/linkButton.vue'
</script>

<template>
  <main>
    <linkButton link="https://oscar.salin.dev">
      <template #text>Oscar</template>
    </linkButton>

    <linkButton>
      <template #text>Coming Soon...</template>
    </linkButton>
  </main>
</template>

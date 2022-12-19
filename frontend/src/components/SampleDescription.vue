<script setup lang="ts">

defineProps<{ text: string }>()
</script>

<template>
  <div class="bg-gray-200 dark:bg-gray-900 w-full">
    <p class="mt-20 p-20">{{ text }}</p>
  </div>
</template>

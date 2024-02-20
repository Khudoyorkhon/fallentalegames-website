<template>
  <button class="text-white px-5 py-3 rounded-md bg-cyan-500">{{ text }}</button>
</template>

<script setup lang="ts">
defineProps<{
  text: string
}>()
</script>
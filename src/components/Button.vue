<template>
  <button class=" text-white">{{ text }}</button>
</template>

<script setup lang="ts">
defineProps<{
  text: string
}>()
</script>
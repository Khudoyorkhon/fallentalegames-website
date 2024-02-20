<template>
  <nav class="p-4 bg-slate-950 flex items-center justify-between">
    <h2 class="text-white text-sm">Fallentale Games</h2>
    <Button :text="'Hello world'" />
  </nav>
</template>

<script setup lang="ts">
import Button from './Button.vue';
</script>
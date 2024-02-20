<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from '@/components/NavBar.vue';
import SideBar from './components/SideBar.vue';
</script>

<template>
  <header>
    <NavBar />
  </header>
  <main class="pt-12 block">
    <SideBar />
  </main>
</template>

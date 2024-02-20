<template>
  <aside class="p-2 pl-5">
    <ul>
      <li class=" font-bold text-white mb-6 last:mb-0" v-for="(i, key) in links" :key="key">
        {{ i.title }}
        
<i class="pi pi-check"></i>
      </li>
    </ul>
  </aside>
</template>

<script setup lang="ts">
import type { Link } from '@/types/link.type';
const links: Link[] = [
    {
      title: 'lorem',
      key: 'lorem1'
    },
    {
      title: 'lorem',
      key: 'lorem1'
    }
  ]
</script>
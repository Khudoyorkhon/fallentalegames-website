<template>
  <aside>
    <ul>
      <li v-for="(i, key) in links" :key="key">
        {{ i.title }}
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
<script setup lang="ts">
defineProps<{
  colorClass: string,
  size: string,
}>()
</script>

<template>
  <svg :class="colorClass" :width="size" :height="size" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg"><g><path d="m11.9995 2c-2.69254 0-4.87523 2.18269-4.87523 4.87518s2.18269 4.87522 4.87523 4.87522c2.6924 0 4.8751-2.18273 4.8751-4.87522s-2.1827-4.87518-4.8751-4.87518z"/><path d="m9.68774 13.2504c-3.17563 0-5.75 2.5743-5.75 5.75v.2496c0 1.5188 1.23122 2.75 2.75 2.75h10.62406c1.5188 0 2.75-1.2312 2.75-2.75v-.2496c0-3.1757-2.5744-5.75-5.75-5.75z"/></g></svg>
</template>

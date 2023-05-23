<template>
  <div
    :class="`flex justify-between bg-white px-4 py-3 rounded-md border-t-4 ${border}`"
  >
    <h4 class="capitalize font-semibold">{{ title }}</h4>
    <span class="font-semibold">{{ count }}</span>
  </div>
</template>

<script setup>
const { border, title, count } = defineProps(['border', 'title', 'count']);
</script>

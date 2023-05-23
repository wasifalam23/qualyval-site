<template>
  <div
    :class="`flex gap-2 p-2 rounded-md py-3 ${
      active ? 'bg-slate-300' : 'bg-white'
    }`"
  >
    <img class="w-12 h-12 rounded-full" :src="image" alt="" />

    <div class="w-full">
      <div class="flex justify-between">
        <h5 class="capitalize font-semibold text-base">{{ name }}</h5>
        <span v-if="day === '1'" class="text-sm text-slate-600"
          >{{ day }} Day ago</span
        >
        <span v-else class="text-sm text-slate-600">{{ day }} Days ago</span>
      </div>

      <div class="flex gap-1">
        <span class="text-sm text-slate-600">Job: </span>
        <p class="capitalize text-sm text-slate-600">{{ role }}</p>
      </div>

      <p class="text-sm capitalize text-slate-700">{{ team }}</p>
    </div>
  </div>
</template>

<script setup>
const { image, day, name, role, team, active } = defineProps([
  'image',
  'day',
  'name',
  'role',
  'team',
  'active',
]);
</script>

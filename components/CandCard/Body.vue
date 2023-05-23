<template>
  <div class="bg-white p-2 rounded-md">
    <div class="flex items-center gap-2 border-b border-b-slate-200 pb-2">
      <img class="w-10 h-10 rounded-full" :src="image" alt="cand-img" />
      <p class="font-semibold capitalize">{{ name }}</p>
    </div>

    <div class="flex justify-between pt-2">
      <div class="flex">
        <StarIcon v-for="n in rating" class="w-5 h-5 text-yellow-400" />
        <StarIcon v-for="n in 5 - rating" class="w-5 h-5 text-gray-300" />
      </div>

      <p>1 day ago</p>
    </div>
  </div>
</template>

<script setup>
import { StarIcon } from '@heroicons/vue/24/solid';

const { image, name, rating } = defineProps(['image', 'name', 'rating']);
</script>

<template>
  <div :class="`bg-white rounded-md px-2 py-2  border-t-4 ${border}`">
    <h3 class="text-2xl font-semibold text-slate-700">{{ title }}</h3>
    <p class="capitalize font-semibold">{{ role }}</p>

    <div class="mt-3">
      <h6 class="text-sm text-slate-600">Candidates:</h6>

      <div class="grid grid-cols-2 bg-slate-300 rounded-md p-2 border-2">
        <div class="border-l-4 border-green-500 pl-2">
          <h4 class="text-sm font-semibold text-slate-600 uppercase">Total</h4>
          <span class="font-semibold">{{ totalC }}</span>
        </div>
        <div class="border-l-4 border-green-500 px-1">
          <h4 class="text-sm font-semibold text-slate-600 uppercase">New</h4>
          <span class="font-semibold">{{ newC }}</span>
        </div>
      </div>
    </div>

    <h3 class="py-2 font-semibold text-lg">Purwokerto, Freelancer</h3>

    <div class="flex justify-between border-t border-r-slate-400 pt-2 pr-2">
      <div class="flex items-center gap-1 text-slate-600">
        <ClipboardDocumentListIcon class="w-6" />
        <span>Draft</span>
      </div>

      <button class="text-slate-600">See Details</button>
    </div>
  </div>
</template>

<script setup>
import { ClipboardDocumentListIcon } from '@heroicons/vue/24/outline';

const { border, title, role, totalC, newC } = defineProps([
  'border',
  'title',
  'role',
  'totalC',
  'newC',
]);
</script>

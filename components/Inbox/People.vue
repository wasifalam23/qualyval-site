<template>
  <div
    class="pr-3 border-r border-gray-200 pt-3 max-md:border-none max-md:pr-0"
  >
    <div class="flex gap-2 w-full">
      <InboxInput />
      <div
        class="border border-slate-300 p-2 flex items-center justify-center rounded-md"
      >
        <FunnelIcon class="w-6 h-6 text-slate-500" />
      </div>
    </div>

    <div class="mt-8 flex flex-col gap-3">
      <InboxPCard
        :image="p1"
        day="1"
        name="brooklyn simmons"
        role="senior UIX designer"
        team="desing team"
      />

      <InboxPCard
        :image="p2"
        day="1"
        name="ronaldo karvia"
        role="UI/UX Designer"
        team="desing team"
      />

      <InboxPCard
        :image="p3"
        day="2"
        name="coddy fisher"
        role="Frontend Developer"
        team="developer team"
        :active="true"
      />

      <InboxPCard
        :image="p4"
        day="4"
        name="Airlen McKoi"
        role="web designer"
        team="Design Team"
      />

      <InboxPCard
        :image="p5"
        day="2"
        name="Darlene robert"
        role="web designer"
        team="Design Team"
      />
    </div>
  </div>
</template>

<script setup>
import p1 from '@/assets/images/pp-1.jpg';
import p2 from '@/assets/images/pp-2.jpg';
import p3 from '@/assets/images/pp-3.jpg';
import p4 from '@/assets/images/pp-4.jpg';
import p5 from '@/assets/images/pp-5.jpg';

import { FunnelIcon } from '@heroicons/vue/24/outline';
</script>

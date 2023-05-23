<template>
  <main>
    <div
      class="text-sm font-medium text-center text-gray-500 border-b border-gray-200 dark:text-gray-400 dark:border-gray-700"
    >
      <ul class="flex flex-wrap -mb-px ml-2">
        <li class="mr-6">
          <a
            href="#"
            class="uppercase text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-700 hover:border-gray-300 text-gray-700"
            >Recruitment inbox</a
          >
        </li>
        <li>
          <a
            href="#"
            class="uppercase text-base font-semibold inline-block p-4 border-b-2 rounded-t-lg"
            aria-current="page"
            >work inbox</a
          >
        </li>
      </ul>
    </div>

    <section class="mx-6 grid grid-cols-[1fr_2fr_1fr]">
      <div class="pr-3 border-r border-slate-300 pt-6">
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
      <div class="p-2">Chat</div>
      <div>People Details</div>
    </section>
  </main>
</template>

<script setup>
import { FunnelIcon } from '@heroicons/vue/24/outline';
import p1 from '@/assets/images/pp-1.jpg';
import p2 from '@/assets/images/pp-2.jpg';
import p3 from '@/assets/images/pp-3.jpg';
import p4 from '@/assets/images/pp-4.jpg';
import p5 from '@/assets/images/pp-5.jpg';
</script>

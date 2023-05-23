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
      <!-- PEOPLE -->
      <InboxPeople />
      <!-- CHAT -->
      <InboxChat />

      <div>People Details</div>
    </section>
  </main>
</template>

<script setup>
import {
  FunnelIcon,
  DocumentTextIcon,
  ArrowDownTrayIcon,
} from '@heroicons/vue/24/outline';
</script>

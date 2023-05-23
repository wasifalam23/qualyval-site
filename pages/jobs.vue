<template>
  <main>
    <div
      class="text-sm font-medium text-center text-gray-500 border-b border-gray-200 dark:text-gray-400 dark:border-gray-700"
    >
      <ul class="flex flex-wrap -mb-px ml-2">
        <li class="mr-8">
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-700 hover:border-gray-300 text-gray-700"
            >Active Jobs</a
          >
        </li>
        <li>
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 rounded-t-lg"
            aria-current="page"
            >Inactive Jobs</a
          >
        </li>
      </ul>
    </div>

    <header class="flex items-center gap-8 mx-6 mt-4">
      <div class="flex items-center gap-2">
        <span class="text-xl font-semibold">7</span>
        <h3 class="text-xl font-semibold">Active Jobs</h3>
      </div>

      <div class="flex items-center gap-2">
        <span class="text-gray-600">Short by:</span>
        <div class="flex items-center">
          <p class="capitalize text-sm font-semibold">creation date</p>
          <ChevronUpDownIcon class="w-4" />
        </div>
      </div>

      <div class="flex items-center gap-2">
        <span class="text-gray-600">Status:</span>
        <div class="flex items-center">
          <p class="capitalize text-sm font-semibold">all status</p>
          <ChevronUpDownIcon class="w-4" />
        </div>
      </div>
    </header>

    <section class="grid grid-cols-4 gap-6 mx-6 mt-6">
      <JobsCard
        class="border-t-orange-500"
        title="Desing"
        role="senior product designer"
        totalC="36"
        newC="5"
      />

      <JobsCard
        class="border-t-green-500"
        title="Desing"
        role="UI/UX designer"
        totalC="36"
        newC="5"
      />

      <JobsCard
        class="border-t-orange-500"
        title="Developer"
        role="senior developer"
        totalC="42"
        newC="2"
      />

      <JobsCard
        class="border-t-green-500"
        title="Desing"
        role="Head of UX"
        totalC="42"
        newC="2"
      />

      <JobsCard
        class="border-t-orange-500"
        title="Marketing"
        role="copywriter"
        totalC="27"
        newC="9"
      />

      <JobsCard
        class="border-t-green-500"
        title="Desing"
        role="senior product designer"
        totalC="36"
        newC="5"
      />
    </section>
  </main>
</template>

<script setup>
import { ChevronUpDownIcon } from '@heroicons/vue/24/outline';
</script>

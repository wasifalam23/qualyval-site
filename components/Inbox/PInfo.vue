<template>
  <section>
    <div
      class="border-b border-b-gray-200 py-4 flex justify-center flex-col items-center"
    >
      <img
        class="w-12 h-12 rounded-full"
        src="@/assets/images/pp-3.jpg"
        alt="job-candidate"
      />
      <p class="capitalize font-semibold">cody fisher</p>
      <button class="capitalize text-sm text-gray-600">View profile</button>
    </div>

    <div class="px-3 py-5 border-b border-b-gray-200 flex flex-col gap-2">
      <div class="flex items-center gap-2">
        <EnvelopeIcon class="w-6 h-6" />
        <p>codyfish@gmail.com</p>
      </div>

      <div class="flex items-center gap-2">
        <PhoneIcon class="w-6 h-6" />
        <p>+916483953567</p>
      </div>
    </div>

    <div class="px-3 py-5 border-b border-b-gray-200">
      <span class="text-xs font-semibold">Applied For:</span>
      <p class="font-semibold">Job: Senior UIX Designer</p>
      <div class="mt-2">
        <p class="text-sm text-gray-600">Design Team</p>
        <div class="flex">
          <StarIcon class="w-4 h-4 text-yellow-400" />
          <StarIcon class="w-4 h-4 text-yellow-400" />
          <StarIcon class="w-4 h-4 text-yellow-400" />
          <StarIcon class="w-4 h-4 text-yellow-400" />
          <StarIcon class="w-4 h-4 text-gray-300" />
        </div>
      </div>
    </div>

    <div class="px-3 py-5 border-b border-b-gray-200">
      <Button class="flex items-center gap-2">
        <PlusCircleIcon class="w-6 h-6 text-blue-700" />
        <span class="text-sm font-semibold"> Add Owner</span>
      </Button>
    </div>

    <div class="px-3 py-5">
      <h6 class="text-sm font-medium">Schedule:</h6>
      <div
        class="mt-2 border border-gray-200 border-l-green-400 border-l-4 rounded-md p-2"
      >
        <p class="text-base font-medium mb-2">
          Allignment for onboarding welcoming new member on product teams
        </p>
        <div
          class="bg-blue-200 w-fit p-1 rounded-md border border-blue-500 mb-2"
        >
          <p class="text-xs text-blue-800 font-medium">Waiting Approval</p>
        </div>
        <p class="text-sm">9 Mar, 2021 7.00-7.45pm</p>
        <button class="mt-3 text-sm font-medium">View Summery</button>
      </div>
    </div>
  </section>
</template>

<script setup>
import { StarIcon } from '@heroicons/vue/24/solid';
import {
  PlusCircleIcon,
  EnvelopeIcon,
  PhoneIcon,
} from '@heroicons/vue/24/outline';
</script>

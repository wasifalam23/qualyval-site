<template>
  <div
    class="pt-3 border-r border-gray-200 max-md:pt-12 max-md:border-none max-md:mb-6"
  >
    <div>
      <header
        class="flex justify-between items-center px-3 border-b border-b-gray-200 pb-3"
      >
        <div>
          <h4 class="capitalize text-sm font-semibold">
            my application for senior developer
          </h4>
          <p>Job: Front-End Developer</p>
        </div>

        <div class="p-1 bg-gray-400 rounded-md flex items-center">
          <button class="bg-white px-3 py-1 rounded-md font-medium">
            Chat
          </button>
          <button class="px-3 py-1 font-medium">Email</button>
        </div>
      </header>

      <div class="inline-flex items-center justify-center w-full relative">
        <hr class="w-full h-px my-8 bg-gray-200 border-0 dark:bg-gray-700" />
        <span
          class="absolute px-3 font-medium text-white -translate-x-1/2 bg-black rounded-full py-1 left-1/2 text-xs"
          >Fri, 2 Jul</span
        >
      </div>

      <div class="px-3 flex flex-col gap-4 max-md:p-0">
        <div class="bg-white rounded-md px-2 py-3 w-2/3">
          <p class="text-base">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Similique
            quisquam obcaecati vero exercitationem totam excepturi expedita fuga
            doloremque quaerat qui.
          </p>
        </div>

        <div class="bg-white w-2/3 px-2 py-3 rounded-md flex gap-2 pr-4">
          <DocumentTextIcon class="w-6 h-6 self-center" />
          <div class="flex justify-between w-full items-center">
            <div>
              <p class="font-semibold text-sm">CV_New.doc</p>
              <span class="text-sm text-gray-600">1.2 Mb</span>
            </div>
            <ArrowDownTrayIcon class="w-5 h-5" />
          </div>
        </div>
      </div>

      <div class="inline-flex items-center justify-center w-full relative">
        <hr class="w-full h-px my-8 bg-gray-200 border-0 dark:bg-gray-700" />
        <span
          class="absolute px-3 font-medium text-white -translate-x-1/2 bg-black rounded-full py-1 left-1/2 text-xs"
          >Today</span
        >
      </div>

      <div class="px-3 flex flex-col gap-4 max-md:p-0">
        <div class="bg-green-300 rounded-md px-2 py-3 w-2/3 self-end">
          <p class="text-base">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt
            qui beatae veniam recusandae nihil.
          </p>
        </div>
        <div class="bg-white rounded-md px-2 py-3 w-2/3">
          <p class="text-base">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab!
          </p>
        </div>
      </div>

      <form class="mt-24 px-3 max-md:mt-8 max-md:p-0">
        <label for="chat" class="sr-only">Your message</label>
        <div
          class="flex items-center px-3 py-2 rounded-lg bg-gray-50 dark:bg-gray-700"
        >
          <button
            type="button"
            class="inline-flex justify-center p-2 text-gray-500 rounded-lg cursor-pointer hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600"
          >
            <svg
              aria-hidden="true"
              class="w-6 h-6"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M4 3a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V5a2 2 0 00-2-2H4zm12 12H4l4-8 3 6 2-4 3 6z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span class="sr-only">Upload image</span>
          </button>
          <button
            type="button"
            class="p-2 text-gray-500 rounded-lg cursor-pointer hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600"
          >
            <svg
              aria-hidden="true"
              class="w-6 h-6"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 100-2 1 1 0 000 2zm7-1a1 1 0 11-2 0 1 1 0 012 0zm-.464 5.535a1 1 0 10-1.415-1.414 3 3 0 01-4.242 0 1 1 0 00-1.415 1.414 5 5 0 007.072 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span class="sr-only">Add emoji</span>
          </button>
          <textarea
            id="chat"
            rows="1"
            class="block mx-4 p-2.5 w-full text-sm text-gray-900 bg-white rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-800 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="Your message..."
          ></textarea>
          <button
            type="submit"
            class="inline-flex justify-center p-2 text-blue-600 rounded-full cursor-pointer hover:bg-blue-100 dark:text-blue-500 dark:hover:bg-gray-600"
          >
            <svg
              aria-hidden="true"
              class="w-6 h-6 rotate-90"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"
              ></path>
            </svg>
            <span class="sr-only">Send message</span>
          </button>
        </div>
      </form>
    </div>
  </div>
</template>

<script setup>
import { DocumentTextIcon, ArrowDownTrayIcon } from '@heroicons/vue/24/outline';
</script>

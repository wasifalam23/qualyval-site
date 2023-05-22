<template>
  <div class="">
    <header class="flex justify-between items-center mx-6">
      <div>
        <h2 class="capitalize text-xl font-semibold">
          senior product designer
        </h2>
        <p class="text-sm text-gray-600">Purwokerto. Full time</p>
      </div>
      <div>
        <button
          type="button"
          class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
        >
          Share and Promote
        </button>
        <button
          type="button"
          class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
        >
          Published
        </button>
      </div>
    </header>

    <div
      class="text-sm font-medium text-center text-gray-500 border-b border-gray-200 dark:text-gray-400 dark:border-gray-700 mt-4"
    >
      <ul class="flex flex-wrap -mb-px ml-2">
        <li class="mr-12">
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-700 hover:border-gray-300 text-gray-700"
            >Candidate</a
          >
        </li>
        <li class="mr-12">
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 rounded-t-lg"
            aria-current="page"
            >Job Details</a
          >
        </li>
        <li class="mr-12">
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300"
            >Time Line</a
          >
        </li>
        <li class="mr-12">
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300"
            >Hiring Team</a
          >
        </li>
        <li>
          <a
            class="text-base font-semibold inline-block p-4 text-gray-400 rounded-t-lg cursor-not-allowed dark:text-gray-500"
            >Settings</a
          >
        </li>
      </ul>
    </div>

    <div class="mx-6 mt-6 flex justify-between">
      <h3 class="capitalize text-base font-medium">
        total candidates:
        <span class="p-1 bg-green-700 text-white font-semibold rounded-sm ml-1">
          22</span
        >
      </h3>

      <div class="flex bg-gray-400 p-1 rounded-md">
        <button class="bg-white px-3 py-1 font-semibold rounded-md">
          Pipeline view
        </button>
        <button class="py-1 px-3 font-semibold rounded-md">Table view</button>
      </div>
    </div>
  </div>
</template>

<script setup></script>

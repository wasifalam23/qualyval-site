<template>
  <main class="mb-8">
    <header
      class="flex justify-between items-center mx-6 mt-6 max-md:flex-col max-md:items-start max-md:gap-4 max-md:mt-8"
    >
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
      <ul class="flex gap-12 flex-wrap -mb-px ml-2 max-xl:gap-5">
        <li>
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-700 hover:border-gray-300 text-gray-700"
            >Candidate</a
          >
        </li>
        <li>
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 rounded-t-lg"
            aria-current="page"
            >Job Details</a
          >
        </li>
        <li>
          <a
            href="#"
            class="text-base font-semibold inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300"
            >Time Line</a
          >
        </li>
        <li>
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

    <div
      class="mx-6 mt-6 flex justify-between items-center max-md:flex-col max-md:items-start max-md:gap-4"
    >
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

    <section
      class="grid grid-cols-4 gap-8 mx-6 mt-6 max-lg:grid-cols-2 max-lg:gap-y-12 max-md:grid-cols-1 max-md:mt-8"
    >
      <div class="flex flex-col gap-4">
        <CandCardHead
          class="border-t-green-500"
          title="New Applied"
          count="10"
        />

        <CandCardBody :image="p1" name="esther gongela" :rating="4" />
        <CandCardBody :image="p2" name="lubrica fannandes" :rating="3" />
        <CandCardBody :image="p3" name="ariyana grozza" :rating="4" />
        <CandCardBody :image="p4" name="john morchien" :rating="4" />
      </div>

      <div class="flex flex-col gap-4">
        <CandCardHead
          class="border-t-yellow-500"
          title="New Applied"
          count="10"
        />

        <CandCardBody :image="p2" name="roushan ambani" :rating="3" />
        <CandCardBody :image="p3" name="rubayet jaman" :rating="3" />
        <CandCardBody :image="p4" name="ray mistirayo" :rating="3" />
      </div>

      <div class="flex flex-col gap-4">
        <CandCardHead
          class="border-t-orange-500"
          title="New Applied"
          count="10"
        />

        <CandCardBody :image="p1" name="esther gongela" :rating="4" />
        <CandCardBody :image="p2" name="lubrica fannandes" :rating="3" />
        <CandCardBody :image="p3" name="ariyana grozza" :rating="3" />
        <CandCardBody :image="p4" name="ariyana grozza" :rating="4" />
      </div>

      <div class="flex flex-col gap-4">
        <CandCardHead
          class="border-t-violet-500"
          title="New Applied"
          count="10"
        />

        <CandCardBody :image="p4" name="shown micalle" :rating="4" />
        <CandCardBody :image="p5" name="stone chold" :rating="3" />
      </div>
    </section>
  </main>
</template>

<script setup>
import p1 from '@/assets/images/pp-1.jpg';
import p2 from '@/assets/images/pp-2.jpg';
import p3 from '@/assets/images/pp-3.jpg';
import p4 from '@/assets/images/pp-4.jpg';
import p5 from '@/assets/images/pp-5.jpg';
</script>

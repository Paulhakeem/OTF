<template>
  <div>
    <header class="mt-6">
      <h1 class="text-center text-[#181d30] text-4xl font-bold">
        Find Your Dream Car
      </h1>

      <div class="mt-6 flex justify-center p-2 bg-white rounded-full w-full">
        <div
          class="flex justify-between divide-x-2 divide-solid divide-gray-300"
        >
          <button
            class="text-gray-500 font-semibold px-4 py-2 cursor-pointer text-md"
          >
            Used Cars
          </button>
          <button class="px-4 cursor-pointer">
            <AnyMakes />
          </button>
          <button class="px-4 cursor-pointer">
            <AnyModel />
          </button>
          <button
            class="text-gray-500 font-semibold px-4 py-2 cursor-pointer text-md"
          >
            All Prices
          </button>
        </div>
      </div>
    </header>
    <main>
     <div >
      <Photo />
     </div>
    </main>
  </div>
</template>
<script setup>
import AnyModel from "./AnyModel.vue";
import AnyMakes from "./AnyMakes.vue";
import Photo from "./Photo.vue";
</script>

<template>
  <main>
    <div class="flex justify-center">
      <img src="../assets/images/range.png" alt="Car" class="w-2xl" />
    </div>

    <div class="justify-center text-center mt-4">
      <h1 class="text-2xl font-bold text-[#181d30]">Browse by Type</h1>

      <div id="type-car" class="grid grid-cols-7 pt-8 mx-4 gap-4">
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'truck-pickup']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Hatchback</p>
        </div>
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'car-side']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Coupe</p>
        </div>
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'car-side']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Hybrid</p>
        </div>
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'car-side']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Convertible</p>
        </div>
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'van-shuttle']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Van</p>
        </div>
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'truck']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Track</p>
        </div>
        <div
          class="bg-white p-8 rounded-md shadow-md flex flex-col items-center justify-center cursor-pointer hover:shadow-lg"
        >
          <font-awesome-icon
            :icon="['fas', 'car-side']"
            class="text-3xl text-gray-600"
          />
          <p class="font-semibold text-md pt-4">Electric</p>
        </div>
      </div>
    </div>

    <!-- main part -->
    <Main />
    <!-- main -->
  </main>
</template>
<script setup>
import Main from "./Main.vue";
</script>

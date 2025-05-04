<template>
  <main class="mt-12 justify-center mx-2 text-center">
    <div class="grid grid-cols-2 items-center justify-center gap-10 mt-8">
      <div class="bg-[#e9f3ff] w-full h-72 rounded-lg">
        <div class="mt-16 text-left pl-10">
          <h2 class="text-3xl font-semibold">
            Are you looking <br />
            for a car?
          </h2>
          <p class="text-gray-500 text-md mt-4">
            We are commited to providing our customers <br />
            with professional services
          </p>

          <div class="flex items-center justify-between mt-6">
            <Button
              class="border-2 border-purple-600 rounded-lg px-3 py-2 text-purple-400 cursor-pointer hover:bg-purple-600 hover:text-purple-200 mt-6"
            >
              GET STARTED
            </Button>
            <font-awesome-icon :icon="['fas', 'car']" class="text-6xl pr-10 text-purple-400"/>
          </div>
        </div>
      </div>
      <div class="bg-[#ffeaf3] w-full h-72 rounded-lg">
        <div class="mt-16 text-left pl-10">
          <h2 class="text-3xl font-semibold">
            Do you want <br />
            to sale car?
          </h2>
          <p class="text-gray-500 text-md mt-4">
            We are commited to providing our customers <br />
            with professional services
          </p>

          <div class="flex items-center justify-between mt-6">
            <Button
              class="border-2 border-purple-600 rounded-lg px-3 py-2 text-purple-400 cursor-pointer hover:bg-purple-600 hover:text-purple-200 mt-6"
            >
              GET STARTED
            </Button>
            <font-awesome-icon :icon="['fas', 'car']" class="text-6xl pr-10 text-purple-400"/>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script setup lang="ts"></script>

<style scoped></style>

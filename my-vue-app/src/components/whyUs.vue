<template>
  <div class="py-10">
    <h2 class="text-2xl font-semibold mb-4">Why Choose Us?</h2>
    <div id="why-us" class="text-start grid grid-cols-4 my-12">
      <div>
        <!-- icon -->
        <Offer />
        <!--  -->
        <div class="mt-4">
          <h4 class="text-lg font-semibold text-gray-800">
            Special financing offers
          </h4>
          <p class="text-gray-600 text-md">
            Our stress-free finance department that can find financial solution
            to save your money.
          </p>
        </div>
      </div>

      <div>
        <!-- icon -->
        <Diamond />
        <!--  -->
        <div class="mt-4">
          <h4 class="text-lg font-semibold text-gray-800">
            Trusted car dealer
          </h4>
          <p class="text-gray-600 text-md">
            Our stress-free finance department that can find financial solution
            to save your money.
          </p>
        </div>
      </div>

      <div>
        <!-- icon -->
        <Price />
        <!--  -->
        <div class="mt-4">
          <h4 class="text-lg font-semibold text-gray-600">
            Transparent Pricing
          </h4>
          <p class="text-gray-600 text-md">
            Our stress-free finance department that can find financial solution
            to save your money.
          </p>
        </div>
      </div>

      <div>
        <!-- icon -->
        <Service />
        <!--  -->
        <div class="mt-4">
          <h4 class="text-lg font-semibold text-gray-800">
            Expert car service
          </h4>
          <p class="text-gray-600 text-md">
            Our stress-free finance department that can find financial solution
            to save your money.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import Diamond from "./icons/Diamond.vue";
import Offer from "./icons/Offer.vue";
import Price from "./icons/Price.vue";
import Service from "./icons/Service.vue";
</script>

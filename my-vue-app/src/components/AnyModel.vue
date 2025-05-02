<template>
  <div>
    <Menu as="div" class="relative inline-block text-left">
      <div>
        <MenuButton
          class="inline-flex w-full justify-center text-md font-medium text-gray-500"
        >
          Any Model
          <span>
            <font-awesome-icon
              class="text-xs ml-6 text-violet-500"
              :icon="['fas', 'circle-chevron-down']"
            />
          </span>
        </MenuButton>
      </div>

      <transition
        enter-active-class="transition duration-100 ease-out"
        enter-from-class="transform scale-95 opacity-0"
        enter-to-class="transform scale-100 opacity-100"
        leave-active-class="transition duration-75 ease-in"
        leave-from-class="transform scale-100 opacity-100"
        leave-to-class="transform scale-95 opacity-0"
      >
        <MenuItems
          class="absolute mt-2 w-44 origin-top-right divide-y divide-gray-100 rounded-md bg-white shadow-lg ring-1 ring-black/5 focus:outline-none"
        >
          <div class="px-1 py-1">
            <MenuItem>
              <button>Edit</button>
            </MenuItem>
      
          </div>
          <div class="px-1 py-1">
            <MenuItem>
              <button>Archive</button>
            </MenuItem>
          </div>

          <div class="px-1 py-1">
            <MenuItem>
              <button>Delete</button>
            </MenuItem>
          </div>
        </MenuItems>
      </transition>
    </Menu>
  </div>
</template>
<script setup lang="ts">
import { Menu, MenuButton, MenuItems, MenuItem } from "@headlessui/vue";
</script>

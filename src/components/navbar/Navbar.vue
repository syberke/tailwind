<template>
  <header class="fixed top-0 left-0 w-full bg-white text-gray-600 body-font shadow z-50">
    <div class="container mx-auto flex flex-wrap p-5 flex-row items-center justify-between">
      
      <!-- Logo -->
      <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
      
        <span class="ml-3 text-xl">Beyond</span>
      </a>

      <!-- Hamburger Button (mobile) -->
      <button
        class="md:hidden inline-flex items-center justify-center p-2 rounded-md text-gray-600 hover:text-gray-900 focus:outline-none"
        @click="open = !open"
      >
        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2"
             viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
          <path v-if="!open" d="M4 6h16M4 12h16M4 18h16"></path>
          <path v-else d="M6 18L18 6M6 6l12 12"></path>
        </svg>
      </button>

      <!-- Nav Menu -->
      <nav
        :class="[
          'flex-col md:flex-row md:flex md:items-center md:space-x-5 md:static md:bg-transparent md:p-0 transition-all duration-300',
          open ? 'flex absolute top-full left-0 w-full bg-white shadow-md p-5 space-y-3' : 'hidden md:flex'
        ]"
      >
        <a class="hover:text-gray-900">Home</a>
        <a class="hover:text-gray-900">Product</a>
        <a class="hover:text-gray-900">About</a>
        <a class="hover:text-gray-900">Contact</a>

        <!-- Login Button -->
        <button
          class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 mt-2 md:mt-0 focus:outline-none hover:bg-gray-200 rounded text-base"
        >
          Login
          <svg fill="none" stroke="currentColor" stroke-linecap="round"
               stroke-linejoin="round" stroke-width="2"
               class="w-4 h-4 ml-1" viewBox="0 0 24 24">
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </nav>

    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'
const open = ref(false)
</script>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import FooterSection from './components/FooterSection.vue';
</script>

<template>
  <header>

    <nav class="bg-white border-gray-200 dark:bg-blue-700">
      <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl p-4">
        <a href="https://flowbite.com" class="flex items-center">
          <img src="https://flowbite.com/docs/images/logo.svg" class="h-8 mr-3" alt="Flowbite Logo" />
          <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Arche Service</span>
        </a>
        <div class="flex items-center">
          <a href="tel:5541251234" class="mr-6 text-sm  text-gray-500 dark:text-white hover:underline">(243)
            826-861-073</a>
        </div>
      </div>
    </nav>

    <nav class="bg-gray-50 dark:bg-gray-700">
      <div class="max-w-screen-xl px-4 py-3 mx-auto">
        <div class="flex items-center">
          <ul class="flex flex-row font-medium mt-0 mr-6 space-x-8 text-sm">
            <li>
              <a href="#" class="text-gray-900 dark:text-white hover:underline" aria-current="page">Accueil</a>
            </li>
            <li>
              <a href="#" class="text-gray-900 dark:text-white hover:underline">Services</a>
            </li>
            <li>
              <a href="#" class="text-gray-900 dark:text-white hover:underline">Boutiques</a>
            </li>
            <li>
              <a href="#" class="text-gray-900 dark:text-white hover:underline">A-propos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

  </header>

  <RouterView />

  <FooterSection />
</template>

<style scoped></style>

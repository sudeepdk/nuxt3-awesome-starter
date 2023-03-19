<script lang="ts" setup>
import { AppConfigInput } from '@nuxt/schema'
import p from './../../package.json'
const app = useAppConfig() as AppConfigInput
</script>

<template>
  <footer class="border-t lg:border-gray-900/10 dark:border-gray-50/[0.2]">
    <section
      class="max-w-8xl mx-auto px-4 lg:px-8 flex-1 flex w-full space-x-20"
    >
      <div class="w-full py-4 text-center md:text-left">
        <div class="mb-1">
          <!-- {{ app.name }} -->
          Kashtabhanjan Holidays
        </div>
        <div class="text-xs text-gray-600 dark:text-gray-400">
          Copyright © 2023
          <a :href="app.author.link">
            Shop No-2 , Kaisalsh Hights , Iraniwadi No 3 , Kandivali west ,
            Mumbai 400067 contact us on - 9773117451 </a
          >. <span class="text-red-500"></span>
          <div
            class="flex flex-col md:flex-row space-x-2 items-center md:float-right"
          >
            <span class="text-center md:text-right">
              Design by <a href="https://diggajcoder.com">Diggaj Coder</a>
            </span>
            <span
              class="block bg-blue-500 rounded px-1 py-0.5 text-white text-xs"
            >
              v1.0
              <!-- {{ p.devDependencies.nuxt }} -->
            </span>
          </div>
        </div>
      </div>
    </section>
  </footer>
</template>

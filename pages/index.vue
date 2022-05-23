<template>
  <div class="h-full flex flex-col">
    <div class="flex-grow-0 flex-shrink-0 h-52 p-5">
      <h3 class="text-2xl font-mono">Projecten</h3>

    </div>
    <div class="flex-grow-0 flex-shrink-0 h-52 bg-gray-200 p-5">
      <h3 class="text-2xl font-mono">Blog</h3>

    </div>
    <div class="flex-grow-0 flex-shrink-0 h-52 p-5">
      <h3 class="text-2xl font-mono">Contact</h3>

    </div>
    <div class="flex-grow-0 flex-shrink-0 h-10 bg-gray-800 text-white text-center p-5">
      <p class="text-xs">Website created with ❤ by <a class="text-blue-400" href="https://www.stal.digital/">Stal.Digital</a>.</p>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  layout: 'default'
})
</script>

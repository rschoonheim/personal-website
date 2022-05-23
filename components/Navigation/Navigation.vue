<template>
  <div>
    <NavigationContainer>
      <NavigationSlot>
        <h1 class="text-xl font-serif">Romano</h1>
        <p class="text-xs">Tweaking since 2004.</p>
      </NavigationSlot>

      <NavigationSlot>
        <div @click="toggleMenu" class="space-y-2">
          <span class="block w-8 h-0.5 bg-gray-600"></span>
          <span class="block w-5 h-0.5 bg-gray-600"></span>
        </div>
      </NavigationSlot>
    </NavigationContainer>

    <ul v-if="showNavigation" class="bg-gray-700 text-white">
      <NuxtLink to="/">
        <li class="p-5 hover:bg-gray-600">Home</li>
      </NuxtLink>
    </ul>
  </div>

</template>

<script lang="ts">
import Vue from 'vue'
import NavigationContainer from "~/components/Navigation/Flex/NavigationContainer.vue";
import NavigationSlot from "~/components/Navigation/Flex/NavigationSlot.vue";

export default Vue.extend({
  name: 'Navigation',
  components: {NavigationSlot, NavigationContainer},
  data() {
    return {
      showNavigation: false,
    };
  },
  methods: {
    toggleMenu(): void {
      this.showNavigation = !this.showNavigation;
    }
  }
})
</script>

<template>
  <div>

    <Navigation
      class="mb-3"
    />

    <Nuxt/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Navigation from "~/components/Navigation/Navigation.vue";

export default Vue.extend({
  name: 'default',
  components: {Navigation}
})
</script>

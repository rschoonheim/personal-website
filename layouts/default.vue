<template>
  <div>

    <Navigation
    />

    Default layout..
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

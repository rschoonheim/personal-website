<template>
  <NavigationContainer>

    <NavigationSlot>
      Row one
    </NavigationSlot>

    <NavigationSlot>
      Row Two
    </NavigationSlot>

  </NavigationContainer>

</template>

<script lang="ts">
import Vue from 'vue'
import NavigationContainer from "~/components/Navigation/Flex/NavigationContainer.vue";
import NavigationSlot from "~/components/Navigation/Flex/NavigationSlot.vue";

export default Vue.extend({
  name: 'Navigation',
  components: {NavigationSlot, NavigationContainer}
})
</script>

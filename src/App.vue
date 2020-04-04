
<template>
  <HelloWorld :greeting="greeting"></HelloWorld>
</template>

<script lang="ts">
import Vue from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default Vue.extend({
  data: function() {
    return {
      greeting: "Hello!"
    };
  },
  components: {
    HelloWorld
  }
});
</script>

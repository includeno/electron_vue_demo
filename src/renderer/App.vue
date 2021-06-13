

<template>
  <div id="app">
    <router-view></router-view>
    <HelloWorld></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "eleapp",
  components: {
    HelloWorld,
  },
};
</script>

<style>
/* CSS */
</style>

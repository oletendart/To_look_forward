<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Body />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Body from "./components/Body";

export default {
  name: "App",
  components: {
    HelloWorld,
    Body
  }
};
</script>

<style>

</style>

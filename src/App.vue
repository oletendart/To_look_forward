<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Body />
    <Footer />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Body from "./components/Body";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    HelloWorld,
    Body,
    Footer
  }
};
</script>

<style>

</style>

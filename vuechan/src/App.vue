<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
import Header from "../src/components/Header";
export default {
  components: {
    Header,
  }
};
</script>

<style scoped>
</style>
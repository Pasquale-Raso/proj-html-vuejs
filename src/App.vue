<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  name: "App",
  components: {
    Header: Header,
  },
};
</script>

<style lang="scss">
@import "./sass/File.scss";
</style>

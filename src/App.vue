<template>
  <div id="app">
    <Header />
    <Jumbotron />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Jumbotron from "@/components/Jumbotron.vue";

export default {
  name: "App",
  components: {
    Jumbotron: Jumbotron,
    Header: Header,
  },
};
</script>

<style lang="scss">
@import "./sass/File.scss";
</style>

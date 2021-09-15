<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Sectionlive />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Jumbotron from "@/components/Jumbotron.vue";
import Sectionlive from "@/components/Sectionlive.vue";

export default {
  name: "App",
  components: {
    Jumbotron: Jumbotron,
    Header: Header,
    Sectionlive: Sectionlive,
  },
};
</script>

<style lang="scss">
@import "./sass/File.scss";
</style>

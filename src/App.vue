<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Sectionlive />
    <Main />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Jumbotron from "@/components/Jumbotron.vue";
import Sectionlive from "@/components/Sectionlive.vue";
import Main from "@/components/Main.vue";

export default {
  name: "App",
  components: {
    Jumbotron: Jumbotron,
    Header: Header,
    Sectionlive: Sectionlive,
    Main: Main,
  },
};
</script>

<style lang="scss">
@import "./sass/File.scss";
</style>

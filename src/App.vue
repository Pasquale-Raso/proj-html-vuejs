<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Sectionlive />
    <Main />
    <Sectionnews />
    <Sectionvideo />
    <Sectiondates />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Jumbotron from "@/components/Jumbotron.vue";
import Sectionlive from "@/components/Sectionlive.vue";
import Main from "@/components/Main.vue";
import Sectionnews from "@/components/Sectionnews.vue";
import Sectionvideo from "@/components/Sectionvideo.vue";
import Sectiondates from "@/components/Sectiondates.vue";

export default {
  name: "App",
  components: {
    Jumbotron: Jumbotron,
    Header: Header,
    Sectionlive: Sectionlive,
    Main: Main,
    Sectionnews: Sectionnews,
    Sectionvideo: Sectionvideo,
    Sectiondates: Sectiondates,
  },
};
</script>

<style lang="scss">
@import "./sass/File.scss";
</style>

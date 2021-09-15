<template>
  <div class="box-header d-flex justify-content-between">
    <!-- logo -->
    <a href="#">
      <img src="@/assets/avada-music-logo.png" alt="" />
    </a>
    <!-- entrata navbar -->
    <div ref="myNav" class="overlay">
      <div class="d-flex justify-content-between p-4">
        <a href="#">
          <img src="@/assets/avada-music-logo.png" alt="" />
        </a>
        <a class="closebtn" @click="closeNav()"> &times;</a>
      </div>
      <div v-for="link in links" :key="link" class="overlay-content">
        <a href="#">{{ link }}</a>
      </div>
    </div>
    <span class="openBtn" @click="openNav()">&#9776;</span>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        "Home",
        "Meet The Band",
        "Live Dates",
        "Latest News",
        "Albums",
        "Fans",
      ],
    };
  },
  methods: {
    //   metodi per apertura e chiusura navbar
    closeNav() {
      this.$refs.myNav.style.width = " 0%";
    },
    openNav() {
      this.$refs.myNav.style.width = "100%";
    },
  },
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
.box-header {
  color: $White-color;
  padding: 30px;
}

// struttura per navbar di ingresso
.overlay {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  right: 0;
  top: 0;
  background-color: $Mandy-color;
  overflow: hidden;
  transition: 0.5s;
}

// pulsanti apertura e chiusura navbar
.closebtn {
  font-weight: bold;
  cursor: pointer;
}
.openBtn {
  font-weight: bold;
  font-size: 36px;
  cursor: pointer;
}

// contenuto interno alla navbar
.overlay-content {
  position: relative;
  width: 100%;
  text-align: center;
  margin-top: 10px;
}
// struttura delle a
.overlay a {
  padding: 5px;
  text-decoration: none;
  font-size: 40px;
  color: $Bombay-color;
  display: block;
  transition: 0.3s;
}

// over delle a
.overlay a:hover,
.overlay a:focus {
  color: $White-color;
}

// gestione respnsive delle a
@media screen and (max-height: 450px) {
  .overlay a {
    font-size: 40px;
    top: 15px;
    right: 35px;
  }
}
</style>
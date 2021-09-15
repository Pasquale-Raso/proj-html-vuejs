<template>
  <div class="jumbotron">
    <div class="container">
      <div class="texts text-center text-white">
        <h1 class="title">Untold Stories</h1>
        <p class="subtitle">There is an untold story every favorites song.</p>
        <button type="button" class="btn-red">LATEST ALBUM</button>
        <button type="button" class="btn-grey">LIVE DATES</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "jumbotron",
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";

.jumbotron {
  background: url("~@/assets/home_slider.jpg") no-repeat center;
  height: 100vh;
  position: relative;
  .texts {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    .title {
      font-size: 100px;
    }
    .subtitle {
      font-size: 20px;
      font-style: italic;
      color: $Bombay-color;
      text-shadow: 2px 2px 4px black;
    }
    .btn-grey,
    .btn-red {
      background-color: transparent;
      color: $Bombay-color;
      border: solid 1px $Bombay-color;
      font-size: 14px;
      padding: 10px 40px 10px 40px;
      margin: 10px;
      margin-top: 20px;
    }
    .btn-grey:hover {
      background-color: $White-color;
      color: $Charade-color;
    }
    .btn-red:hover {
      background-color: $Mandy-color;
      color: $White-color;
      border: solid 1px $Mandy-color;
    }
  }
}
</style>
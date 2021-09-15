<template>
  <div class="box-sectionlive">
    <div class="container">
      <div class="red-line"></div>
      <h1 class="pt-5">Music Is Life</h1>
      <div class="grey-line"></div>
      <p class="subtitle pt-5 pb-4">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
        sunt, non nulla quo iste ex incidunt laborum, inventore distinctio totam
        libero architecto voluptas! Quae quia consectetur ipsam. Totam, debitis
        et.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sectionlive",
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
.box-sectionlive {
  background-color: $Charade2-color;
  position: relative;
  text-align: center;
  color: $White-color;
  height: 250px;
  .red-line {
    height: 10px;
    width: 400px;
    background-color: $Mandy-color;
    position: absolute;
    left: 50%;
    top: -2%;
    transform: translate(-50%, 50%);
  }
  .grey-line {
    height: 1px;
    width: 200px;
    background-color: $MidGray-color;
    position: absolute;
    left: 50%;
    top: 45%;
    transform: translate(-50%, -50%);
  }
  .subtitle {
    color: $MidGray-color;
    font-size: 12px;
    padding-left: 150px;
    padding-right: 150px;
  }
}
</style>
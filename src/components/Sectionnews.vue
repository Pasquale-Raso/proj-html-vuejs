<template>
  <div class="box-sectionnews">
    <button type="button" class="btn-big">VIEW ALL LATEST NEWS</button>
  </div>
</template>

<script>
export default {
  name: "Sectionnews",
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
.box-sectionnews {
  background-color: $Mandy-color;
  margin-top: -100px;
  height: 120px;
}
.btn-big {
  background-color: transparent;
  color: $White-color;
  border: 0;
  font-size: 17px;
  text-align: center;
  width: 100%;
  height: 120px;
}

.btn-big:hover {
  background-color: $White-color;
  color: $Charade-color;
  transition: 0.5s;
}
</style>
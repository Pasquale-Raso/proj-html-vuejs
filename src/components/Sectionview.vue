<template>
  <div class="box-Sectionview">
    <button type="button" class="btn-big">VIEW ALL LIVE DATES</button>
  </div>
</template>

<script>
export default {
  name: "Sectionview",
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
.box-Sectionview {
  background-color: $Mandy-color;

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
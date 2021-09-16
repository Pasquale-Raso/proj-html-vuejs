<template>
  <div class="Sectionvideo">
    <div class="container">
      <div class="citazione">
        <cite
          >"Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat,
          officia. Ad adipisci maxime sint tempore molestiae voluptate minus
          magni numquam recusandae doloribus dignissimos, quidem velit veritatis
          eaque consequatur. Quaerat, quae?"</cite
        >
        <div>
          <img
            class="player"
            src="@/assets/band_interview_play_icon.png"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  nome: "Sectionvideo",
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
.Sectionvideo {
  background: url("~@/assets/home-testimonial-parallax.jpg") no-repeat center;
  height: 100vh;
  position: relative;

  .citazione {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    color: $White-color;
    text-align: center;
    padding-left: 150px;
    padding-right: 150px;
    font-size: 20px;

    .player {
      width: 60px;
      margin-top: 20px;
      cursor: pointer;

      &:hover {
        transform: scale(1.1);
        filter: invert(1);
      }
    }
  }
}
</style>
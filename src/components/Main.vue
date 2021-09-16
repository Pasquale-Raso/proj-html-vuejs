<template>
  <div class="box-main">
    <!-- intestazione -->
    <div class="box-main-heading">
      <div class="container">
        <h1 class="pt-5">Latest Band News</h1>
        <div class="grey-line"></div>
        <p class="subtitle pt-5 pb-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
          sunt, non nulla quo iste ex incidunt laborum, inventore distinctio
          totam libero architecto voluptas! Quae quia consectetur ipsam. Totam,
          debitis et.
        </p>
      </div>
    </div>
    <!-- card -->
    <div class="container text-white">
      <div class="row">
        <div class="col-md-8">
          <div class="card">
            <div class="card dissolvenza">
              <p class="text-img-hover">Technology and music</p>
              <img
                src="@/assets/blog_music_techo.jpg"
                class="card-img-top img-horizontal"
              />
            </div>
            <div class="card-body">
              <h5 class="card-title">Technology and music</h5>
              <p class="card-text text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam
                deleniti facere riure accusantium amet!
              </p>
            </div>
          </div>
        </div>
        <div class="col-6 col-md-4">
          <div class="card">
            <div class="card dissolvenza">
              <p class="text-img-hover">Taking it back to the old school</p>
              <img src="@/assets/blog-post1-600x900.jpg" class="card-img-top" />
            </div>
            <div class="card-body">
              <h5 class="card-title">Taking it back to the old school</h5>
              <p class="card-text text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam
                deleniti facere riure accusantium amet!
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-6 col-md-4">
          <div class="card" style="top: -18rem">
            <div class="card dissolvenza">
              <p class="text-img-hover">While my guitar gently weeps</p>
              <img src="@/assets/blog-post3-600x900.jpg" class="card-img-top" />
            </div>
            <div class="card-body">
              <h5 class="card-title">While my guitar gently weeps</h5>
              <p class="card-text text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam
                deleniti facere riure accusantium amet!
              </p>
            </div>
          </div>
        </div>
        <div class="col-6 col-md-4">
          <div class="card" style="top: -18rem">
            <div class="card dissolvenza">
              <p class="text-img-hover">It just sounds better</p>
              <img src="@/assets/blog-post4.jpg" class="card-img-top" />
            </div>
            <div class="card-body">
              <h5 class="card-title">It just sounds better</h5>
              <p class="card-text text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam
                deleniti facere riure accusantium amet!
              </p>
            </div>
          </div>
        </div>
        <div class="col-6 col-md-4">
          <div class="card" style="top: 28px">
            <div class="card dissolvenza">
              <p class="text-img-hover">Sharing the stage wth a legend</p>
              <img src="@/assets/blog-post2-600x900.jpg" class="card-img-top" />
            </div>
            <div class="card-body">
              <h5 class="card-title">Sharing the stage wth a legend</h5>
              <p class="card-text text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam
                deleniti facere riure accusantium amet!
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-8">
          <div class="card .card-bg" style="top: -16rem">
            <div class="card dissolvenza">
              <p class="text-img-hover">The flavor of rock</p>

              <img
                src="@/assets/blog_flavor_rock-1200x600.jpg"
                class="card-img-top img-horizontal"
              />
            </div>
            <div class="card-body">
              <h5 class="card-title">The flavor of rock</h5>
              <p class="card-text text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam
                deleniti facere riure accusantium amet!
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "main",
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
.box-main {
  background-color: $Charade-color;

  .box-main-heading {
    position: relative;
    text-align: center;
    color: $White-color;
    height: 250px;

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
  .img-horizontal {
    height: 170px;
    width: auto;
    object-fit: cover;
  }
  .card {
    background-color: $card-cap-bg;
    position: relative;
  }
  .dissolvenza {
    background: $Mandy-color;
    padding: -2px;
    border-color: $card-cap-bg;
  }
  img:hover {
    transition: 0.5s;
    filter: opacity(30%);
    -webkit-filter: opacity(30%);
  }
  .text-img-hover {
    position: absolute;
    left: 50%;
    top: 40%;
    transform: translate(-50%, 50%);
    visibility: hidden;
    font-weight: bold;
    text-align: center;
  }
  .dissolvenza:hover .text-img-hover {
    visibility: visible;
  }
}
</style>
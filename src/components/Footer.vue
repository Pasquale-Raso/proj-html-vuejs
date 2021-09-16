<template>
  <div>
    <div class="box-footerSu">
      <div class="d-flex justify-content-between">
        <!-- logo -->
        <a href="#">
          <img src="@/assets/logo_footer.png" alt="" />
        </a>
        <div class="d-flex">
          <li v-for="link in links" :key="link">
            <a href="#">{{ link }}</a>
          </li>
        </div>
      </div>
    </div>
    <div class="box-footerIn">
      <div class="d-flex justify-content-between align-items-center">
        <p class="copy">
          &#169; Copyright 2021-2022 | AVADA THEME BY THEMEFUSION | ALL RIGHTS
          RESERVED | POWERED PASQUALE RASO
        </p>
        <div class="d-flex">
          <link
            rel="stylesheet"
            href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"
          />
          <div class="center">
            <div id="social-test">
              <ul class="social">
                <li><i class="fa fa-facebook" aria-hidden="true"></i></li>
                <li><i class="fa fa-twitter" aria-hidden="true"></i></li>
                <li><i class="fa fa-instagram" aria-hidden="true"></i></li>
                <li><i class="fa fa-vimeo" aria-hidden="true"></i></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
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
  methods: {},
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";

.box-footerSu {
  background-color: $card-cap-bg;
  color: $White-color;
  padding: 30px;
  height: 150px;
  list-style-type: none;
  li {
    margin-top: 30px;
  }
  a {
    text-decoration: none;
    font-size: 15px;
    color: $Bombay-color;
    transition: 0.3s;
    margin-bottom: 10px;
    padding: 20px 10px 0px 10px;
  }

  a:hover {
    color: $White-color;
  }
}
.box-footerIn {
  background-color: $Charade-color;
  color: $White-color;
  padding: 30px;
  height: 90px;
  list-style-type: none;
  .copy {
    font-size: 11px;
    color: $Bombay-color;
  }

  #social-test {
    display: table-cell;
    text-align: center;
    font-size: 15px;

    li {
      color: $Bombay-color;
      list-style-type: none;
      display: inline-block;
      width: 35px;
      height: 35px;
      padding: 8px;

      background-color: $card-cap-bg;
      cursor: pointer;
      margin-left: 10px;

      transition: ease 0.3s;
      &:hover {
        color: $White-color;
      }
    }
  }
  .social:hover > li {
    opacity: 0.5;
  }

  .social:hover > li:hover {
    opacity: 1;
  }
}
</style>
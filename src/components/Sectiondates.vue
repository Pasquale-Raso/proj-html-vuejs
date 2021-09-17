<template>
  <div class="box-main">
    <!-- intestazione -->
    <div class="box-main-heading">
      <div class="container">
        <h1 class="pt-5">Live Dates</h1>
        <div class="grey-line"></div>
        <p class="subtitle pt-5 pb-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
          sunt, non nulla quo iste ex incidunt laborum, inventore distinctio.
        </p>
      </div>
    </div>
    <!-- menù accordion -->
    <div class="container">
      <div class="accordion">
        <div class="message" :class="accordionClasses">
          <div class="message-header" @click="toggleAccordion">
            17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
          </div>
          <div class="message-body">
            <div class="message-content d-flex">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d11140.873905030096!2d-83.73907695176412!3d9.164057415477373!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8fa15797d4474891%3A0x39ea10029c9e9f27!2sProvincia%20di%20Puntarenas%2C%20Uvita%2C%20Costa%20Rica!5e0!3m2!1sit!2sit!4v1631805980160!5m2!1sit!2sit"
                width="300"
                height="250"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
              ></iframe>
              <div class="info">
                <p class="title">ANAKALIA</p>
                <p class="subtitle-card">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Consequuntur quos numquam sit reprehenderit, at ut, officiis
                  repudiandae velit voluptates quod placeat eum quas
                  consectetur, itaque quasi fugit sapiente repellendus aliquam.
                </p>
                <button type="button" class="btn-red">BOOK NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="message" :class="accordionClasses">
          <div class="message-header" @click="toggleAccordion">
            24/09/2020 GROVEFEST DOMINICAL REPUBLIC
          </div>
          <div class="message-body">
            <div class="message-content d-flex">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1935300.8917429857!2d-71.25128882265261!3d18.669175818860364!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8eaf8838def1b6f5%3A0xa6020f24060df7e0!2sRepubblica%20Dominicana!5e0!3m2!1sit!2sit!4v1631875264552!5m2!1sit!2sit"
                width="300"
                height="250"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
              ></iframe>
              <div class="info">
                <p class="title">DOMINICAL REPUBLIC</p>
                <p class="subtitle-card">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Consequuntur quos numquam sit reprehenderit, at ut, officiis
                  repudiandae velit voluptates quod placeat eum quas
                  consectetur, itaque quasi fugit sapiente repellendus aliquam.
                </p>
                <button type="button" class="btn-red">BOOK NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="message" :class="accordionClasses">
          <div class="message-header" @click="toggleAccordion">
            31/08/2020 OASIS FESTIVAL 2020 MARRAKECH, MOROCCO
          </div>
          <div class="message-body">
            <div class="message-content d-flex">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d108702.95033111013!2d-8.077893024321316!3d31.634748491216005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xdafee8d96179e51%3A0x5950b6534f87adb8!2sMarrakech%2C%20Marocco!5e0!3m2!1sit!2sit!4v1631875628974!5m2!1sit!2sit"
                width="300"
                height="250"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
              ></iframe>
              <div class="info">
                <p class="title">MARRAKECH</p>
                <p class="subtitle-card">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Consequuntur quos numquam sit reprehenderit, at ut, officiis
                  repudiandae velit voluptates quod placeat eum quas
                  consectetur, itaque quasi fugit sapiente repellendus aliquam.
                </p>
                <button type="button" class="btn-red">BOOK NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="message" :class="accordionClasses">
          <div class="message-header" @click="toggleAccordion">
            07/11/2020 MOGA FESTIVAL - ESSAOURIA, MOROCCO
          </div>
          <div class="message-body">
            <div class="message-content d-flex">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d27211.83858618933!2d-9.780051740599463!3d31.510978945160115!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xdad9a4e9f588ccf%3A0x57421a176d5d7d30!2sProvincia%20di%20Essaouira%2C%20Marocco!5e0!3m2!1sit!2sit!4v1631877043102!5m2!1sit!2sit"
                width="300"
                height="250"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
              ></iframe>
              <div class="info">
                <p class="title">ESSAOURIA</p>
                <p class="subtitle-card">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Consequuntur quos numquam sit reprehenderit, at ut, officiis
                  repudiandae velit voluptates quod placeat eum quas
                  consectetur, itaque quasi fugit sapiente repellendus aliquam.
                </p>
                <button type="button" class="btn-red">BOOK NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="message" :class="accordionClasses">
          <div class="message-header" @click="toggleAccordion">
            10/12/2020 ENVISION FESTIVAL UVITA, COSTA RICA
          </div>
          <div class="message-body">
            <div class="message-content d-flex">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15755.606614150829!2d-83.74680521645772!3d9.163344128767946!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8fa15797d4474891%3A0x39ea10029c9e9f27!2sProvincia%20di%20Puntarenas%2C%20Uvita%2C%20Costa%20Rica!5e0!3m2!1sit!2sit!4v1631877226427!5m2!1sit!2sit"
                width="300"
                height="250"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
              ></iframe>
              <div class="info">
                <p class="title">UVITA</p>
                <p class="subtitle-card">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Consequuntur quos numquam sit reprehenderit, at ut, officiis
                  repudiandae velit voluptates quod placeat eum quas
                  consectetur, itaque quasi fugit sapiente repellendus aliquam.
                </p>
                <button type="button" class="btn-red">BOOK NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sectiondates",
  data() {
    return {
      isOpen: false,
    };
  },
  methods: {
    toggleAccordion() {
      this.isOpen = !this.isOpen;
    },
  },
  computed: {
    accordionClasses() {
      return {
        "is-closed": !this.isOpen,
      };
    },
  },
};
</script>

<style scoped lang="scss">
@import "./src/sass/Variables.scss";
// intestazione
.box-main {
  background-color: $Charade-color;
  padding-bottom: 80px;

  .box-main-heading {
    position: relative;
    text-align: center;
    color: $White-color;
    height: 250px;
  }
  .grey-line {
    height: 1px;
    width: 200px;
    background-color: $MidGray-color;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
  }
  .subtitle {
    color: $MidGray-color;
    font-size: 12px;
    padding-left: 150px;
    padding-right: 150px;
  }

  // menù accordion
  .accordion {
    background-color: $card-cap-bg;
    color: $White-color;
    margin-bottom: 10px;
  }
  .message-header {
    cursor: pointer;
    color: $Mandy-color;
    font-size: 20px;
    padding: 15px;
  }
  .message-body {
    height: 300px;
    overflow: hidden;
  }
  .is-closed .message-body {
    max-height: 0;
  }
  .message-content {
    padding: 15px;
  }
  .title {
    margin-left: 30px;
    font-size: 20px;
  }
  .subtitle-card {
    color: $MidGray-color;
    margin-left: 30px;
    font-size: 15px;
    line-height: 42px;
  }
  .btn-red {
    background-color: $Mandy-color;
    color: $White-color;
    border: solid 1px $Mandy-color;
    font-size: 14px;
    padding: 10px 40px 10px 40px;
    margin: 10px;
    margin-top: 20px;
    margin-left: 30px;
  }
  .btn-red:hover {
    background-color: $White-color;
    color: $Charade-color;
    border: solid 1px $White-color;
  }
}
</style>
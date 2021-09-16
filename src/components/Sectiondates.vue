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
        <article class="message" :class="accordionClasses">
          <div class="message-header" @click="toggleAccordion">
            17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
          </div>
          <div class="message-body">
            <div class="message-content">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </div>
          </div>
        </article>
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
        "is-primary": this.isOpen,
        "is-dark": !this.isOpen,
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
  height: 700px;

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
  }
  .message {
    width: 500px;
  }

  .message-header {
    cursor: pointer;
    color: $Mandy-color;
    font-size: 12px;
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
}
</style>
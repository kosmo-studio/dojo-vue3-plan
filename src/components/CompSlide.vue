<template>
  <CarouselMain
    :slides="slides"
    :interval="3000"
    controls
    indicators
  ></CarouselMain>
</template>

<script lang="ts">
import CarouselMain from "./componentCarousel/CarouselMain.vue";
import CompHeaderVue from "./CompHeader.vue";

export default {
  name: "CompSlide",
  components: { CarouselMain, CompHeaderVue },
  data: () => ({
    slides: [
      "src/assets/slide-01-pai.jpg",
      "src/assets/slide-02-casa.png",
      "src/assets/slide-01-pai.jpg",
    ],
  }),
};
</script>

<style scoped></style>

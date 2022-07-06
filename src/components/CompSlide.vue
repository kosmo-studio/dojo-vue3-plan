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

export default {
  name: "CompSlide",
  components: { CarouselMain },
  data: () => ({
    slides: [
      "https://picsum.photos/id/1032/900/400",
      "https://picsum.photos/id/1033/900/400",
      "https://picsum.photos/id/1037/900/400",
      "https://picsum.photos/id/1035/900/400",
      "https://picsum.photos/id/1036/900/400",
    ],
  }),
};
</script>

<style scoped></style>

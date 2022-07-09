<template>
  <v-carousel cycle interval="3000" max-width="1900px" height="800px">
    <v-carousel-item
      v-for="(slide, i) in slides"
      :key="i"
      :src="slide.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
    </v-carousel-item>
  </v-carousel>
</template>

<script lang="ts">
export default {
  name: "CompSlide",
  components: {},
  data: () => ({
    slides: [
      {
        src: "src/assets/img/slide-02-casa.png",
      },
      {
        src: "src/assets/img/slide-01-pai.jpg",
      },
      {
        src: "src/assets/img/slide-02-casa.png",
      },
    ],
  }),
};
</script>

<style scoped></style>

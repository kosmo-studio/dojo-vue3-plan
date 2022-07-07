<template>
  <v-carousel>
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
        src: "src/assets/slide-02-casa.png",
      },
      {
        src: "src/assets/slide-01-pai.jpg",
      },
      {
        src: "src/assets/slide-02-casa.png",
      },
    ],
  }),
};
</script>

<style scoped></style>

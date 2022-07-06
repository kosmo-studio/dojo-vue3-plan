<template>
  <div>
    <div class="slides fade">
      <img src="src/assets/paiefilha.jpg" alt="" />
    </div>
    <div class="slides fade">
      <img src="src/assets/casas.png" alt="" />
    </div>
  </div>
  <div style="text-align: center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>
</template>

<script lang="ts">
export default {
  name: "CompSlide",
  data() {
    return {
      slideIndex: 0,
    };
  },
  methods: {
    showSlides(n) {
      let i;
      let slides = document.getElementsByClassName("slides");
      let dots = document.getElementsByClassName("dot");
    },
  },
};
</script>

<style lang="scss" scoped></style>

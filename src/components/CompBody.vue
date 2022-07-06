<template>
  <div>
    <CompHeader />
    <CompSlide />
  </div>
</template>

<script lang="ts">
import CompHeader from "./CompHeader.vue";
import CompSlide from "./CompSlide.vue";

export default {
  name: "CompBody",
  components: {
    CompHeader,
    CompSlide,
  },
};
</script>

<style lang="scss" scoped></style>

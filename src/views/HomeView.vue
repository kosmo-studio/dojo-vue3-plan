<template>
  <CompHeader />
  <CompSlide />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import CompSlide from "@/components/CompSlide.vue";
import CompHeader from "@/components/CompHeader.vue";

export default defineComponent({
  name: "HomeView",

  components: {
    CompSlide,
    CompHeader,
  },
});
</script>

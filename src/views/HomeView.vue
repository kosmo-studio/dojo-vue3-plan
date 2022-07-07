<template>
  <main class="appMain">
    <CompHeader class="headerMain" />
    <CompSlide />
    <CompBody />
  </main>
</template>

<script lang="ts">
import CompHeader from "@/components/CompHeader.vue";
import CompSlide from "@/components/CompSlide.vue";
import CompBody from "@/components/CompBody.vue";

export default {
  name: "App",
  components: {
    CompBody,
    CompHeader,
    CompSlide,
  },
};
</script>

<style>
.headerMain {
}

.appMain {
  position: relative;
  width: 95em;
  overflow: hidden;
}
</style>

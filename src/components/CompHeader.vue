<script lang="ts">
export default {
  name: "CompHeader",
  data: () => ({}),
};
</script>
<template>
  <v-app-bar width="100%" height="200">
    <v-card width="20%"></v-card>
    <v-card class="d-flex" width="63%" height="180" color="#000C3D">
      <div class="pa-4 align-self-center">
        <v-img
          height="68.48"
          width="220"
          aspect-ratio="1"
          src="src/assets/img/LogoPlan.png"
        ></v-img>
      </div>
      <div class="align-self-end">
        <div>
          <p>SAC 0800-607-7779</p>
          <v-icon></v-icon>
          <v-icon></v-icon>
          <v-icon></v-icon>
          <v-btn></v-btn>
          <v-btn></v-btn>
        </div>

        <div></div>
      </div>
    </v-card>
  </v-app-bar>
</template>

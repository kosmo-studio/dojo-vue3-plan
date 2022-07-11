<script lang="ts">
export default {
  name: "CompHeader",
  data: () => ({}),
};
</script>
<template>
  <v-app-bar width="100%" height="120">
    <v-row justify="space-around">
      <div
        width="63%"
        max-height="120"
        class="ma-6 d-flex align-center bg-blue"
      >
        <div class="pa-4 pr-15 d-flex align-self-center">
          <v-img
            height="100%"
            width="200"
            aspect-ratio="1"
            src="src/assets/img/LogoPlan.png"
          ></v-img>
        </div>

        <v-spacer></v-spacer>

        <div class="ma-4">
          <v-row justify="end">
            <span class="ma-5 text-white"> SAC 0800-607-7779</span>
            <v-icon
              class="ma-5"
              icon="fa:fas fa-lock"
              large
              color="green darken-2"
            >
            </v-icon>
            <v-icon
              class="ma-5"
              large
              icon="fa:fas fa-lock"
              color="green darken-2"
            >
            </v-icon>
            <v-icon
              class="ma-5"
              large
              icon="fa:fas fa-lock"
              color="green darken-2"
            >
            </v-icon>
            <v-btn class="ma-5 bg-green" color="white">Trabalhe Conosco</v-btn>
            <v-btn class="ma-5 bg-green" color="white">Area do Cliente</v-btn>
          </v-row>
          <span></span>
          <v-row justify="end">
            <v-btn color="white">Home</v-btn>
            <v-btn color="white">Empreendimentos</v-btn>
            <v-btn color="white">ESG</v-btn>
            <v-btn color="white">Compre um lote</v-btn>
            <v-btn color="white">Sobre nós</v-btn>
            <v-btn color="white">Fale com a gente</v-btn>
          </v-row>
        </div>
      </div>
    </v-row>
  </v-app-bar>
</template>

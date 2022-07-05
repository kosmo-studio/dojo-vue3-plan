<script setup lang="ts"></script>
<template>
  <div class="header-01">
    <div class="header-02">
      <img src="src/assets/LogoPlan.png" id="logo" alt="Logo de Empresa Plan" />
      <div>
        <span> SAC 0800-607-7779</span>
        <button>facebook</button>
        <button>instagram</button>
        <button>LinkedIn</button>
        <button>Trabalhe Conosco</button>
        <button>Area do Cliente @</button>
      </div>

      <div>
        <button>Home</button>
        <button>Empreendimentos</button>
        <button>ESG</button>
        <button>Compre um lote</button>
        <button>Sobre nós</button>
        <button>Fale com a gente</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.header-01 {
  position: absolute;
  width: 1920px;
  height: 147px;
  left: 0px;
  top: 0px;

  /*  background: l
    inear-gradient(180deg, #85acb4 39.12%, rgba(138, 180, 188, 0) 100%);
  mix-blend-mode: normal; */
}

.header-02 {
  position: absolute;
  width: 1200px;
  height: 120px;
  left: 360px;
  top: 20px;

  background: #000c3d;
  opacity: 0.9;
  border-radius: 10px;
}
#logo {
  width: 220px;
  height: 68.48px;
}
</style>

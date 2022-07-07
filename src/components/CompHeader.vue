<script setup lang="ts"></script>
<template class="headerApp">
  <div class="headerContainer">
    <div class="headerItem-01">
      <img
        src="src/assets/LogoPlan.png"
        class="logo"
        alt="Logo de Empresa Plan"
      />
    </div>
    <div class="headerItem-02">
      <div class="headerMenuItems01">
        <p class="item001">SAC <strong>0800-607-7779</strong></p>
        <div>
          <icon class="item001"
            ><font-awesome-icon icon="fa-brands fa-facebook-square"
          /></icon>
          <icon class="item001"
            ><font-awesome-icon icon="fa-brands fa-instagram"
          /></icon>
          <icon class="item001"
            ><font-awesome-icon icon="fa-brands fa-linkedin"
          /></icon>
        </div>
        <button class="item001">Trabalhe Conosco</button>
        <button class="item001">Area do Cliente @</button>
      </div>

      <div class="headerBorder"></div>

      <div class="headerMenuItems01">
        <button class="item001">Home</button>
        <button class="item001">Empreendimentos</button>
        <button class="item001">ESG</button>
        <button class="item001">Compre um lote</button>
        <button class="item001">Sobre nós</button>
        <button class="item001">Fale com a gente</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.headerApp {
  position: absolute;
}
.headerContainer {
  display: grid;
  grid-template-columns: auto auto;
  width: 80em;
  height: 5em;
  margin: 5em 7em 0 7em;
  background: #000c3d;
  border-radius: 10px;
  padding: 1.7em;
  color: white;
  font-size: 14px;
}

.headerItem-01 {
  grid-column: 1 / span 4;
}

.logo {
  width: 190px;
  height: 58.48px;
}

.headerItem-02 {
  justify-items: end;
  grid-column: 5 / span 6;
}

.headerMenuItems01 {
  display: flex;
  justify-content: end;
  align-items: center;
}

font-awesome-icon {
  margin-right: 1em;
  background-color: white;
}

button {
  background-color: #4caf50; /* Green */
  border: none;
  color: white;
  padding: 5px 5px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}

.p.strong {
  font-weight: bold;
}

.item001 {
  margin: 0 0.5em 0 0.5em;
}

.headerBorder {
  margin-top: 10px;
  margin-bottom: 10px;
  border-bottom: 1px solid white;
}

.headerMenuItems02 {
  display: flex;
  justify-content: end;
  align-items: center;
}
</style>

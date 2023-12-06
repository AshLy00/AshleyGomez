<script setup></script>
<template>
  <div class="grid_education">
    <div class="languaje">
      <h1>languaje</h1>
      <p>spanish (first languaje)</p>
      <p>english (b1 i'm learning :d)</p>
    </div>
    <div class="soft">
      <h1>soft skills</h1>
      <p>creative</p>
    </div>
    <div class="line"></div>
    <div class="education">
      <h1>education</h1>
      <p>
        instituto tecnico de comercio / tecnico en asistente administrativo
        bilingue (20xx - 2022)
      </p>
      <p>
        lci barranquilla / tecnico en produccion grafica digital (2022 - 2023)
      </p>
    </div>
  </div>
</template>

<style scoped>
.grid_education {
  text-transform: uppercase;
  display: grid;
  grid-template-columns: 1fr 0.2fr 1fr;
  grid-template-rows: 1fr 1fr;
  width: 80%;
  align-items: center;
}
.line {
  width: 2px;
  height: 200px;
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;
}
.education {
  grid-column: 3 / 4;
  grid-row: 1 / 3;
}
.soft {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
  justify-items: end;
}

.line {
  grid-column: 2 / 3;
  grid-row: 1 / 3;
  justify-self: center;
}
</style>

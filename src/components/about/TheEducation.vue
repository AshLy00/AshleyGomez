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
        lci barranquilla / tecnologo en produccion grafica digital (2022 - 2023)
      </p>
    </div>
  </div>
</template>

<style scoped>
.languaje {
  color: var(--color-yellow);
  text-align: left;
}
.grid_education {
  text-transform: uppercase;
  display: grid;
  grid-template-columns: 0.2fr 0.1fr 0.2fr;
  grid-template-rows: 1fr 1fr;
  width: 95%;
  align-items: center;
  margin-top: 60px;
  margin-bottom: 60px;
  justify-content: center;
}
.grid_education h1 {
  font-size: 2.5rem;
}
.grid_education p {
  color: black;
  font-size: 0.8rem;
}
.languaje,
.soft,
.education {
  display: flex;
  flex-direction: column;
  gap: 10px;
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
  color: var(--color-blue);
  text-align: end;
}
.soft {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
  justify-items: end;
  color: var(--color-pink);
  text-align: left;
}

.line {
  grid-column: 2 / 3;
  grid-row: 1 / 3;
  justify-self: center;
}
</style>

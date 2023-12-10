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
  text-align: justify;
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

@media screen and (max-width: 1460px) {
  .grid_education {
    text-transform: uppercase;
    display: grid;
    grid-template-columns: 0.3fr 0.1fr 0.3fr;
    grid-template-rows: 1fr 1fr;
    width: 80%;
    align-items: center;
    margin-top: 60px;
    margin-bottom: 60px;
    justify-content: center;
  }
}

@media screen and (max-width: 1300px) {
  .grid_education {
    text-transform: uppercase;
    display: grid;
    grid-template-columns: 0.4fr 0.1fr 0.4fr;
    grid-template-rows: 1fr 1fr;
    width: 70%;
    align-items: center;
    margin-top: 60px;
    margin-bottom: 60px;
    justify-content: center;
  }
}

@media screen and (max-width: 1120px) {
  .grid_education {
    text-transform: uppercase;
    display: grid;
    grid-template-columns: 0.5fr 0.1fr 0.5fr;
    grid-template-rows: 1fr 1fr;
    width: 75%;
    align-items: center;
    margin-top: 60px;
    margin-bottom: 60px;
    justify-content: center;
  }
}
@media screen and (max-width: 915px) {
  .grid_education {
    text-transform: uppercase;
    display: grid;
    grid-template-columns: 0.6fr 0.1fr 0.6fr;
    grid-template-rows: 1fr 1fr;
    width: 75%;
    align-items: center;
    margin-top: 60px;
    margin-bottom: 60px;
    justify-content: center;
  }
}

@media screen and (max-width: 850px) {
  .grid_education {
    text-transform: uppercase;
    display: grid;
    grid-template-columns: 0.6fr 0.1fr 0.6fr;
    grid-template-rows: 1fr 1fr;
    width: 75%;
    align-items: center;
    margin-top: 60px;
    margin-bottom: 60px;
    justify-content: center;
  }
  .grid_education h1 {
    font-size: 2rem;
  }
  .grid_education p {
    color: black;
    font-size: 0.7rem;
  }
}

@media screen and (max-width: 780px) {
  .grid_education {
    text-transform: uppercase;
    display: grid;
    grid-template-columns: 0.6fr 0.1fr 0.6fr;
    grid-template-rows: 1fr 1fr;
    width: 85%;
    align-items: center;
    margin-top: 60px;
    margin-bottom: 60px;
    justify-content: center;
  }
  .grid_education h1 {
    font-size: 2rem;
  }
  .grid_education p {
    color: black;
    font-size: 0.7rem;
  }
}

@media screen and (max-width: 650px) {
  .grid_education {
    display: flex;
    width: 70%;
    margin-top: 60px;
    margin-bottom: 60px;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }
  .line {
    display: none;
  }
  .grid_education h1 {
    font-size: 1.8rem;
  }
  .grid_education p {
    color: black;
    font-size: 0.8rem;
  }
  .education,
  .soft,
  .languaje {
    text-align: left;
  }
}

@media screen and (max-width: 560px) {
  .grid_education {
    display: flex;
    width: 70%;
    margin-top: 30px;
    margin-bottom: 40px;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }
  .line {
    display: none;
  }
  .grid_education h1 {
    font-size: 1.3rem;
  }
  .grid_education p {
    color: black;
    font-size: 0.6rem;
  }
  .education,
  .soft,
  .languaje {
    text-align: left;
  }
}
</style>

<script setup></script>

<template>
  <div class="hero_container">
    <div>
      <h1>ACA VA EL HERO XD</h1>
      <p>Aca va mas texto que no tengo :c</p>
    </div>
    <div> <img src="https://drive.google.com/file/d/1L11xH05iafayjCrJWMO7cACjqjuRhReN/view?usp=sharing" /></div>
  </div>
</template>

<style scoped>
.hero_container {
  background-color: grey;
  height: 600px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
img {
  height: 600px;
}
@media screen and (max-width: 900px) {
  .hero_container {
    height: 200px;
  }
  img {
  }
}
</style>

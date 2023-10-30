<script setup></script>

<template>
  <div class="hero_container">
    <div>
      <h1>ACA VA EL HERO XD</h1>
      <p>Aca va mas texto que no tengo :c</p>
    </div>

    <img src="/Yop.png" />
  </div>
</template>

<style scoped>
.hero_container {
  background-color: red;
  height: 600px;
  display: flex;
  justify-content: space-between;
}
img {
  width: 660px;
  height: 600px;
}
@media screen and (max-width: 900px) {
  .hero_container {
    height: 200px;
  }
  img {
    width: 260px;
    height: 200px;
  }
}
</style>

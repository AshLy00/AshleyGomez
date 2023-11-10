<script setup>
import TheHeader from "./components/app/TheHeader.vue";
import TheHero from "./components/app/TheHero.vue";
import TheIntro from "./components/app/TheIntro.vue";
import TheCategory from "./components/app/TheCategory.vue";
</script>

<template>
  <TheHeader />
  <main>
    <TheHero />
    <TheIntro />
    <div class="categories">
      <TheCategory />
      <TheCategory />
      <TheCategory />
      <TheCategory />
    </div>
  </main>
  <footer></footer>
</template>

<style scoped>
.categories {
  display: flex;
  gap: 50px;
  justify-content: center;
  align-items: center;
  margin: 50px 0px;
}

@media screen and (max-width: 1580px) {
  .categories {
    display: grid;
    grid-template-columns: 300px 300px;
    gap: 50px;
     justify-content: center;
  }
}
</style>

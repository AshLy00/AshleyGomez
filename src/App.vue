<script setup>
import TheHeader from "./components/app/TheHeader.vue";
import TheHero from "./components/app/TheHero.vue";
import TheIntro from "./components/app/TheIntro.vue";
import TheCategory from "./components/app/TheCategory.vue";
</script>

<template>
  <TheHeader />
  <TheHero />
  <TheIntro />
  <div class="categorys">
    <TheCategory />
    <TheCategory />
    <TheCategory />
    <TheCategory />
  </div>
  <main></main>
  <footer></footer>
</template>

<style scoped>
.categorys{
  display: flex;
  gap: 50px;
  height: 450px;
  justify-content: center;
  align-items: center;
}
</style>

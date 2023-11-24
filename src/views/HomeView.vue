<script setup>
import TheHero from "./../components/app/TheHero.vue";
import TheIntro from "./../components/app/TheIntro.vue";
import TheCategory from "./../components/app/TheCategory.vue";
import TheBanner from "./../components/app/TheBanner.vue";
import TheShowcase from "./../components/app/TheShowcase.vue";
import TheGallery from "./../components/app/TheGallery.vue";
</script>
<template>
  <TheHero />
  <TheIntro />
  <section class="categories">
    <TheCategory />
    <TheCategory />
    <TheCategory />
    <TheCategory />
  </section>
  <TheBanner />
  <TheShowcase />
</template>

<style scoped>
.categories {
  display: flex;
  gap: 50px;
  justify-content: center;
  align-items: center;
  margin: 50px 0px;
}

@media screen and (max-width: 1000px) {
  .categories {
    display: grid;
    grid-template-columns: 300px 300px;
    gap: 30px;
    justify-content: center;
  }
}

@media screen and (max-width: 740px) {
  .categories {
    grid-template-columns: 250px 250px;
    gap: 15px;
    margin: 40px 0px;
  }
}

@media screen and (max-width: 580px) {
  .categories {
    grid-template-columns: 200px 200px;
    gap: 15px;
  }
}

@media screen and (max-width: 460px) {
  .categories {
    grid-template-columns: 180px 180px;
    gap: 15px;
    margin: 30px 0px;
  }
}
@media screen and (max-width: 460px) {
  .categories {
    grid-template-columns: 150px 150px;
    gap: 10px;
    margin: 20px 0px;
  }
}

@media screen and (max-width: 350px) {
  .categories {
    grid-template-columns: 120px 120px;
    gap: 5px;
  }
}
</style>

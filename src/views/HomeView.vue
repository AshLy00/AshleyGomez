<script setup>
import TheHero from "./../components/home/TheHero.vue";
import TheIntro from "./../components/home/TheIntro.vue";
import TheCategory from "./../components/home/TheCategory.vue";
import TheBanner from "./../components/home/TheBanner.vue";
import TheShowcase from "./../components/home/TheShowcase.vue";
import SecondBanner from "../components/home/SecondBanner.vue";
import { useRouter } from "vue-router";

const router = useRouter();

// Lista de imágenes correspondientes a cada categoría
const categoryImages = {
  ilustracion:
    "https://drive.google.com/uc?export=view&id=1h9T1hF51zncrVvB6sdUy_yVNh_jDjwoU",
  web: "https://drive.google.com/uc?export=view&id=1h9T1hF51zncrVvB6sdUy_yVNh_jDjwoU",
  animacion:
    "https://drive.google.com/uc?export=view&id=1fjxgouc9AvmVe39al4zaZGgPac7QXL2L",
  modelado:
    "https://drive.google.com/uc?export=view&id=1h9T1hF51zncrVvB6sdUy_yVNh_jDjwoU",
};
</script>
<template>
  <TheHero />
  <TheIntro />
  <section class="categories">
    <TheCategory
      @click="
        () => router.push({ name: 'gallery', params: { id: 'ilustracion' } })
      "
      category="ilustracion"
      :image="categoryImages.ilustracion"
    />
    <TheCategory
      @click="() => router.push({ name: 'gallery', params: { id: 'web' } })"
      category="web"
      :image="categoryImages.web"
    />
    <TheCategory
      @click="
        () => router.push({ name: 'gallery', params: { id: 'animacion' } })
      "
      category="animacion"
      :image="categoryImages.animacion"
    />
    <TheCategory
      @click="() => router.push({ name: 'gallery', params: { id: '3d' } })"
      category="3d"
      :image="categoryImages.modelado"
    />
  </section>
  <TheBanner />
  <TheShowcase />
  <SecondBanner />
</template>

<style scoped>
.categories {
  display: flex;
  gap: 50px;
  justify-content: center;
  align-items: center;
  margin: 50px 0px;
  text-transform: uppercase;
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
    gap: 12px;
    margin: 30px 0px;
  }
}

@media screen and (max-width: 430px) {
  .categories {
    grid-template-columns: 170px 170px;
    gap: 15px;
  }
}

@media screen and (max-width: 380px) {
  .categories {
    grid-template-columns: 150px 170px;
    gap: 15px;
  }
}
</style>

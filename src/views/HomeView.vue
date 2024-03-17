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
  illustration:
    "https://firebasestorage.googleapis.com/v0/b/ashley-portafolio.appspot.com/o/ilustraci%C3%B3n_icon.png?alt=media&token=72e63085-7899-46fa-bfd9-869efb1c52ce",
  web: "https://firebasestorage.googleapis.com/v0/b/ashley-portafolio.appspot.com/o/026.PNG?alt=media&token=cafa8efd-631e-4c2f-9d5b-df7ba40f3166",
  animation:
    "https://firebasestorage.googleapis.com/v0/b/ashley-portafolio.appspot.com/o/003.gif?alt=media&token=2906932f-b482-435f-a4e5-ce92afcf4d9c",
  modelado:
    "https://firebasestorage.googleapis.com/v0/b/ashley-portafolio.appspot.com/o/002.jpg?alt=media&token=347bba15-7759-4c41-ac2a-f63992db3d70",
};
</script>
<template>
  <TheHero />
  <TheIntro />
  <section class="categories">
    <TheCategory
      @click="
        () => router.push({ name: 'gallery', params: { id: 'illustration' } })
      "
      category="illustration"
      :image="categoryImages.illustration"
    />
    <TheCategory
      @click="() => router.push({ name: 'gallery', params: { id: 'web' } })"
      category="web"
      :image="categoryImages.web"
    />
    <TheCategory
      @click="
        () => router.push({ name: 'gallery', params: { id: 'animation' } })
      "
      category="animation"
      :image="categoryImages.animation"
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
  cursor: pointer;
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

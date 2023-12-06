<script setup>
import TheGalleryItem from "./TheGalleryItem.vue";
import TheFilterButtons from "./TheFilterButtons.vue";
import TheBannerGallery from "./TheBannerGallery.vue";
import { database } from "../../database";
import { ref, onMounted, watch } from "vue";
import { useRoute } from "vue-router";

const show = ref([]);
const route = useRoute();
const db = ref(database);
onMounted(() => {
  show.value = db.value.filter((e) => {
    return e.category == route.params.id;
  });
  if (route.params.id == "all") {
    show.value = db.value;
  }
});

watch(
  () => route.params.id,
  () => {
    console.log(route.params.id);

    show.value = db.value.filter((e) => {
      return e.category == route.params.id;
    });

    if (route.params.id == "all") {
      show.value = db.value;
    }
  }
);
</script>
<template>
  <TheBannerGallery />
  <div class="filters_buttons">
    <TheFilterButtons category="ilustracion" />
    <TheFilterButtons category="web" />
    <TheFilterButtons category="animacion" />
    <TheFilterButtons category="3d" />
  </div>
  <div class="gallery_grid">
    <TheGalleryItem v-for="(p, i) in show" :key="i" :project="p" />
  </div>
</template>

<style scoped>
.filters_buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  align-items: center;
  justify-content: center;
  padding: 2rem 0rem;
}
.gallery_grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 20px;
  margin-bottom: 50px;
}

@media screen and (max-width: 1080px) {
  .gallery_grid {
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px;
  }
}

@media screen and (max-width: 700px) {
  .gallery_grid {
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
  .filters_buttons {
    width: 100%;
  }
}

@media screen and (max-width: 560px) {
  .gallery_grid {
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
}
@media screen and (max-width: 370px) {
  .gallery_grid {
    grid-template-columns: 1fr 1fr;
    gap: 15px;
  }
}

@media screen and (max-width: 340px) {
  .filters_buttons {
    gap: 10px;
    padding: 1.5rem 0rem;
  }
}
</style>

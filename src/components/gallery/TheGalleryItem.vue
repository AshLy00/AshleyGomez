<script setup>
const props = defineProps({
  project: Object,
});
</script>
<template>
  <a :href="project.external_link" class="gallery_item">
    <img class="imagezoom" :src="project.images_url" alt="" />
    <div class="overlay">
      <div class="text_hover_gallery">
        <p>{{ project.title }}</p>
        <p>{{ project.description }}</p>
      </div>
    </div>
  </a>
</template>

<style scoped>
.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  background-color: transparent;
  opacity: 0;
}

.overlay .text_hover_gallery {
  color: var(--color-white);
  position: absolute;
  top: 38%;
  left: 18%;
  display: flex;
  flex-direction: column;
  text-shadow: var(--color-black) 1px 0 3px;
}
.text_hover_gallery p {
  width: 80%;
}
.gallery_item:hover .overlay {
  opacity: 1;
}

.gallery_item {
  height: 320px;
  width: 320px;
  overflow: hidden;
  border-radius: 30px;
  position: relative;
  text-align: center;
  cursor: pointer;
  justify-content: center;
  display: flex;
}
.gallery_item img {
  height: 100%;
  display: block;
}
.gallery_item img:hover {
  transform: scale(1.5);
}

@media screen and (max-width: 1520px) {
  .gallery_item {
    height: 270px;
    width: 270px;
  }
}
@media screen and (max-width: 1420px) {
  .gallery_item {
    height: 250px;
    width: 250px;
  }
}

@media screen and (max-width: 1220px) {
  .gallery_item {
    height: 230px;
    width: 230px;
  }
}

@media screen and (max-width: 850px) {
  .gallery_item {
    height: 200px;
    width: 200px;
  }
}

@media screen and (max-width: 700px) {
  .gallery_item {
    height: 220px;
    width: 220px;
  }
}

@media screen and (max-width: 560px) {
  .gallery_item {
    height: 200px;
    width: 200px;
  }
}

@media screen and (max-width: 500px) {
  .gallery_item {
    height: 180px;
    width: 180px;
  }
}

@media screen and (max-width: 430px) {
  .gallery_item {
    height: 150px;
    width: 150px;
    border-radius: 20px;
  }
}
@media screen and (max-width: 370px) {
  .gallery_item {
    height: 140px;
    width: 140px;
  }
}
@media screen and (max-width: 340px) {
  .gallery_item {
    height: 130px;
    width: 130px;
  }
}

@media screen and (max-width: 310px) {
  .gallery_item {
    height: 115px;
    width: 115px;
  }
}
</style>

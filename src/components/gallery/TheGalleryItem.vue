<script setup></script>
<template>
  <div class="gallery_item">
    <img
      src="https://drive.google.com/uc?export=view&id=1Qlyq0mFIL3XzSjw73HmFEgAH87NKuUms"
      alt=""
    />
  </div>
</template>

<style scoped>
.gallery_item {
  height: 320px;
  width: 320px;
  overflow: hidden;
  border-radius: 30px;
}
.gallery_item img {
  width: 100%;
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
    height: 180px;
    width: 180px;
  }
}

@media screen and (max-width: 460px) {
  .gallery_item {
    height: 150px;
    width: 150px;
  }
}

@media screen and (max-width: 360px) {
  .gallery_item {
    height: 120px;
    width: 120px;
    border-radius: 20px;
  }
}
@media screen and (max-width: 320px) {
  .gallery_item {
    height: 110px;
    width: 110px;
  }
}
</style>

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

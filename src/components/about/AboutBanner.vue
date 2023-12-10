<script setup></script>

<template>
  <section class="banner_container">
    <div class="banner_text_container"></div>
    <div class="banner_img_container">
      <img
        src="https://drive.google.com/uc?export=view&id=1eaWilkwljEjz48oIhh5nbcxmLkqbhgRe"
        alt=""
      />
    </div>
  </section>
</template>
<style scoped>
.banner_img_container {
  display: flex;
  justify-content: center;
  align-items: center;
  align-items: center;
  width: 100%;
  height: 500px;
  overflow: hidden;
}

.banner_img_container img {
  width: 100%;
}

.banner_container {
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

@media screen and (max-width: 1550px) {
  .banner_img_container {
    height: 500px;
  }
}

@media screen and (max-width: 1390px) {
  .banner_container {
    height: 500px;
  }
}

@media screen and (max-width: 1275px) {
  .banner_img_container {
    height: 300px;
  }
  .banner_container {
    height: 300px;
  }
}

@media screen and (max-width: 1000px) {
  .banner_img_container {
    height: 250px;
  }
  .banner_container {
    height: 250px;
  }
}

@media screen and (max-width: 880px) {
  .banner_img_container {
    height: 211px;
  }
  .banner_container {
    height: 210px;
  }
}
@media screen and (max-width: 700px) {
  .banner_text_container {
    gap: 10px;
  }
  .banner_img_container {
    height: 200px;
  }
  .banner_container {
    height: 200px;
  }
}

@media screen and (max-width: 570px) {
  .banner_img_container {
    height: 200px;
  }
}
@media screen and (max-width: 470px) {
  .banner_img_container {
    height: 160px;
  }
  .banner_container {
    height: 160px;
  }
}

@media screen and (max-width: 390px) {
  .banner_img_container {
    height: 140px;
  }
  .banner_container {
    height: 140px;
  }
}
@media screen and (max-width: 315px) {
  .banner_img_container {
    height: 100px;
  }
  .banner_container {
    height: 100px;
  }
}
</style>

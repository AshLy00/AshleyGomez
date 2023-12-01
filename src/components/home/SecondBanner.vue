<script setup></script>

<template>
  <section class="banner_container">
    <div class="banner_text_container">
      <h1>FANART</h1>
    </div>
    <div class="banner_img_container">
      <img
        src="https://drive.google.com/uc?export=view&id=1X59PCiV1Rib4-LPAbxvZkXU1hZf5-7oh"
        alt=""
      />
    </div>
  </section>
</template>
<style scoped>
.banner_text_container {
  position: absolute;
  z-index: 1;
  color: var(--color-white);
  gap: 20px;
  display: flex;
  text-shadow: var(--color-black) 1px 0 3px;
  max-width: 1660px;
  text-align: center;
  align-items: center;
}

.banner_text_container h1 {
  font-size: 14rem;
  width: 90%;
}

.banner_img_container {
  display: flex;
  justify-content: center;
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
}

@media screen and (max-width: 1550px) {
  .banner_text_container h1 {
    font-size: 12rem;
  }
  .banner_img_container {
    height: 400px;
  }
}

@media screen and (max-width: 1390px) {
  .banner_container {
    height: 400px;
  }
  .banner_text_container h1 {
    font-size: 10rem;
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
    height: 200px;
  }
  .banner_text_container h1 {
    font-size: 8rem;
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
    height: 155px;
  }

  .banner_text_container h1 {
    font-size: 5rem;
  }
}

@media screen and (max-width: 570px) {
  .banner_img_container {
    height: 150px;
  }
}
@media screen and (max-width: 470px) {
  .banner_img_container {
    height: 160px;
  }
  .banner_container {
    height: 160px;
  }
  .banner_text_container h1 {
    font-size: 4rem;
  }
}

@media screen and (max-width: 390px) {
  .banner_img_container {
    height: 140px;
  }
  .banner_container {
    height: 140px;
  }
  .banner_text_container h1 {
    font-size: 3rem;
  }
}
@media screen and (max-width: 315px) {
  .banner_img_container {
    height: 100px;
  }
  .banner_container {
    height: 100px;
  }
  .banner_text_container h1 {
    font-size: 2rem;
  }
}
</style>

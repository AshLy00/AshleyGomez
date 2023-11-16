<script setup></script>

<template>
  <div class="hero_container">
    <div class="hero_text_container">
      <h1>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT</h1>
      <p>
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR
        SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET
        CONSECTETUR ADIPISCING
      </p>
    </div>
    <div class="hero_img_container">
      <img
        src="https://drive.google.com/uc?export=view&id=1UnBSbdjNL3H9ZFDY8AA5gybePzQm5RA9"
        alt=""/>
    </div>
  </div>
</template>

<style scoped>
.hero_container {
  height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 1660px;
}

.hero_img_container {
  align-self: end;
}

.hero_img_container img {
  object-fit: cover;
  width: 600px;
  height: 100%;
}

.hero_text_container {
  position: relative;
  left: 100px;
}

.hero_text_container h1 {
  font-size: 3.5rem;
}

.hero_text_container p {
  font-size: 1.5rem;
  width: 70%;
}

@media screen and (max-width: 1350px) {
  .hero_text_container h1 {
    font-size: 3rem;
  }

  .hero_text_container p {
    font-size: 1.2rem;
  }

  .hero_container {
    height: 550px;
  }

  .hero_img_container img {
    width: 520px;
  }
}

@media screen and (max-width: 1160px) {
  .hero_text_container h1 {
    font-size: 2.5rem;
  }

  .hero_text_container p {
    font-size: 1rem;
  }

  .hero_container {
    height: 450px;
    right: 10px;
  }

  .hero_img_container img {
    width: 480px;
  }
}

@media screen and (max-width: 970px) {
  .hero_text_container h1 {
    font-size: 2.1rem;
  }

  .hero_text_container p {
    font-size: 0.8rem;
  }

  .hero_container {
    height: 350px;
    right: 20px;
  }

  .hero_img_container img {
    width: 380px;
  }
}

@media screen and (max-width: 900px) {
  .hero_text_container h1 {
    font-size: 2.1rem;
  }

  .hero_text_container p {
    font-size: 0.8rem;
  }

  .hero_container {
    height: 340px;
    right: 20px;
  }

  .hero_img_container img {
    width: 350px;
  }

  .hero_text_container {
    left: 73px;
  }
}

@media screen and (max-width: 770px) {
  .hero_text_container h1 {
    font-size: 1.9rem;
  }

  .hero_text_container p {
    font-size: 0.5rem;
  }

  .hero_container {
    height: 280px;
  }

  .hero_img_container img {
    width: 310px;
  }

  .hero_text_container {
    left: 60px;
  }
}

@media screen and (max-width: 670px) {
  .hero_text_container h1 {
    font-size: 1.5rem;
  }

  .hero_text_container p {
    font-size: 0.5rem;
  }

  .hero_container {
    height: 230px;
  }

  .hero_img_container img {
    width: 250px;
    right: 20px;
  }

  .hero_text_container {
    left: 60px;
  }
}

@media screen and (max-width: 580px) {
  .hero_text_container h1 {
    font-size: 1.2rem;
  }

  .hero_text_container p {
    font-size: 0.5rem;
  }

  .hero_container {
    height: 230px;
  }

  .hero_img_container img {
    width: 240px;
    right: 20px;
  }

  .hero_text_container {
    left: 60px;
  }
}
</style>

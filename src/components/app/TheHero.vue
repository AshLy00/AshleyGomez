<script setup></script>

<template>
  <div class="hero_container">
    <div class="hero_text_container">
      <h1>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT</h1>
      <p>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING</p>
    </div>
    <div class="hero_img_container">
      <img src="https://drive.google.com/uc?export=view&id=1UnBSbdjNL3H9ZFDY8AA5gybePzQm5RA9" alt="">
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
  border: 1px solid transparent;
  align-self: end;
}

.hero_img_container img {
  object-fit: cover;
  width: 600px;
  height: 100%;
}

.hero_text_container {
  border: 1px solid transparent;
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
</style>
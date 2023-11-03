<script setup></script>

<template>
  <div class="hero_container">
    <div class="hero_text_container">
      <h1>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT</h1>
      <p>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING</p>
    </div>
    <div class="hero_img_container"> <img src="Yop.png" /></div>
  </div>
</template>

<style scoped>
.hero_container {
  background-color: grey;
  height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.hero_img_container {
  width: 630px;
  height: 560px;
  align-self: flex-end;
  display: flex;
}

.hero_img_container img{
  width: 100%;
  height: 100%;
  z-index: 5;
}

.hero_text_container{
  width:760px;
  display: flex;
  flex-direction: column;
  gap: 30px;
}

.hero_text_container h1{
font-size: 3.5rem;
}

.hero_text_container p{
font-size: 1.5rem;
width: 70%;
}

@media screen and (max-width: 1650px) {
  .hero_img_container {
  width: 600px;
  height: 530px;
}
.hero_text_container{
  width:650px;
}
.hero_text_container h1{
font-size: 3rem;
}

.hero_text_container p{
font-size: 1.2rem;
width: 90%;
}
}

@media screen and (max-width: 1350px) {
  .hero_container {
  height: 500px;
}
  .hero_img_container {
  width: 550px;
  height: 480px;
}
.hero_text_container{
  width:600px;
}
.hero_text_container h1{
font-size: 2.5rem;
}

.hero_text_container p{
font-size: 1.1rem;
width: 90%;
}
}
</style>

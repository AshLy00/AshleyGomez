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
  height: 560px;
  display: flex;
  position: absolute;
  top: 150px;
  right: 260px;
}

.hero_img_container img{
height: 100%;
}

.hero_text_container{
  width:760px;
  display: flex;
  position: absolute;
  left: 320px;
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

@media screen and (max-width: 1780px) {
  .hero_text_container{
  left: 200px;
}
.hero_img_container {
  right: 220px;
}
}

@media screen and (max-width: 1600px) {
  .hero_text_container{
  left: 160px;
}
.hero_img_container {
  right: 200px;
}
}

@media screen and (max-width: 1580px) {
  .hero_text_container{
  left: 120px;
}
.hero_img_container {
  right: 150px;
}
}

@media screen and (max-width: 1475px) {
  .hero_text_container{
  left: 100px;
}
.hero_img_container {
  right: 120px;
}
}

@media screen and (max-width: 1410px) {
  .hero_text_container{
  left: 80px;
}
.hero_img_container {
  right: 100px;
}

}

@media screen and (max-width: 1380px) {
  .hero_container {
  height: 500px;
}
  .hero_text_container{
  left: 140px;
}

.hero_img_container {
  top: 135px;
  right: 100px;
}
.hero_img_container img{
height: 85%;
}
.hero_text_container h1{
font-size: 3rem;
}

.hero_text_container p{
font-size: 1rem;
width: 70%;
}
}

@media screen and (max-width: 1300px) {
  .hero_text_container{
  left: 120px;
}
.hero_img_container {
  right: 100px;
}
}
</style>

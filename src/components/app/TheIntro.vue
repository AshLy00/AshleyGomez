<script setup></script>

<template>
  <div class="bedroom.jpg" alt="">
    <div class="intro_text_container">
      <h1>PORTAFOLIO</h1>
      <p>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING</p>
    </div>
  </div>
</template>

<style scoped>
.intro_container{
    width:100%;
    height:500px;
    overflow:hidden;
    position: relative;
    display: inline-block;
    display: flex;
    align-items: center;
}
.intro_container img{
    width:100%;
}
.intro_text_container{
  position: absolute;
  top:100px;
  left:15%;
  color:var(--color-white);
  width: 70%;
  text-align: center;
  gap: 20px;
}

.intro_text_container h1{
font-size: 10rem;
}

.intro_text_container p{
font-size: 1.5rem;
}
</style>
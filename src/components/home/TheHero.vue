<script setup></script>

<template>
  <section class="hero_container">
    <div class="hero_text_container">
      <h1>¡HELLO EVERYONE! :b</h1>
      <p>
        TRANSFORMAR CONCEPTOS EN EXPERIENCIAS A TRAVES DEL DISEÑO, DAR VIDA A
        LAS IDEAS Y ESTRECHAR EL ABISMO ENTRE LO TANGIBLE Y LO IMAGINARIO
      </p>
    </div>
    <div class="hero_img_container">
      <img
        src="https://drive.google.com/uc?export=view&id=1v6ie3kY2RaheaAvzpVS1b3PxrlKLuRA7"
        alt=""
      />
    </div>
  </section>
</template>

<style scoped>
.hero_container {
  height: 550px;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  align-items: center;
  max-width: 1360px;
}

.hero_img_container {
  align-self: end;
  right: 20px;
}

.hero_img_container img {
  object-fit: cover;
  width: 600px;
  height: 100%;
}

.hero_text_container {
  position: relative;
  left: 80px;
  gap: 10px;
  display: flex;
  flex-direction: column;
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
  .hero_text_container {
    left: 60px;
  }

  .hero_text_container p {
    font-size: 1.2rem;
  }

  .hero_img_container img {
    width: 480px;
  }
  .hero_container {
    height: 450px;
    max-width: 1100px;
  }
}

@media screen and (max-width: 1160px) {
  .hero_text_container h1 {
    font-size: 2.6rem;
  }

  .hero_text_container p {
    font-size: 1.2rem;
    width: 80%;
  }

  .hero_img_container img {
    width: 450px;
  }
  .hero_text_container {
    left: 50px;
  }

  .hero_container {
    height: 420px;
    max-width: 990px;
  }
}

@media screen and (max-width: 970px) {
  .hero_text_container h1 {
    font-size: 2.1rem;
  }

  .hero_text_container p {
    font-size: 1rem;
  }

  .hero_container {
    height: 350px;
    max-width: 800px;
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
    height: 320px;
  }

  .hero_img_container img {
    width: 350px;
  }

  .hero_text_container {
    left: 50px;
  }
}

@media screen and (max-width: 770px) {
  .hero_text_container h1 {
    font-size: 2rem;
  }

  .hero_text_container p {
    font-size: 0.8rem;
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

@media screen and (max-width: 740px) {
  .hero_text_container h1 {
    font-size: 2rem;
  }

  .hero_text_container p {
    font-size: 0.8rem;
  }

  .hero_container {
    height: 280px;
  }

  .hero_img_container img {
    width: 280px;
  }

  .hero_text_container {
    left: 40px;
  }
}

@media screen and (max-width: 670px) {
  .hero_text_container h1 {
    font-size: 1.7rem;
  }

  .hero_text_container p {
    font-size: 0.6rem;
    width: 70%;
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

@media screen and (max-width: 640px) {
  .hero_text_container h1 {
    font-size: 1.5rem;
  }

  .hero_text_container p {
    font-size: 0.7rem;
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

@media screen and (max-width: 670px) {
  .hero_container {
    height: 380px;
    display: flex;
    flex-direction: column;
    justify-content: end;
    align-items: center;
    width: 100%;
    left: 0;
  }

  .hero_text_container {
    justify-content: center;
    display: flex;
    flex-direction: column;
    position: absolute;
    text-align: center;
    align-items: center;
    top: 50px;
    left: 2%;
    row-gap: 10px;
  }
  .hero_text_container h1 {
    font-size: 1.6rem;
  }

  .hero_text_container p {
    font-size: 0.8rem;
    width: 70%;
  }

  .hero_img_container {
    align-self: center;
  }

  .hero_img_container img {
    right: -3px;
  }
}

@media screen and (max-width: 450px) {
  .hero_text_container h1 {
    font-size: 1.5rem;
  }

  .hero_text_container p {
    font-size: 0.7rem;
    width: 70%;
  }
  .hero_img_container img {
    right: -5px;
  }
}

@media screen and (max-width: 390px) {
  .hero_text_container h1 {
    font-size: 1.5rem;
  }

  .hero_text_container p {
    font-size: 0.7rem;
    width: 80%;
  }

  .hero_img_container img {
    right: -7px;
  }
}
</style>

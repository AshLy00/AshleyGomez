<script setup></script>

<template>
  <section class="banner_container">
    <div class="banner_text_container">
      <h1>MY PROJECTS</h1>
      <p>
        I AM PASSIONATE ABOUT GRAPHIC DESIGN AND ILLUSTRATION. I BELIEVE IN THE
        IMPORTANCE OF TRANSFORMING IDEAS INTO REALITY TO MAKE THE WORLD A BETTER
        PLACE, WHERE EVERYONE CAN SEE THEIR DREAMS COME TO TRUE. I'M HERE TO
        TURN YOUR IDEAS INTO REALITY. <br />
        <br />YOU ALSO CLICK ON SOME OF MY PROJECTS AND SEE THEM BETTER! :D
      </p>
    </div>
    <div class="banner_img_container">
      <img
        src="https://drive.google.com/uc?export=view&id=1qDrPfFgTBCpkrSp1juT4Dmh8Ggxp_-95"
        alt=""
      />
    </div>
  </section>
</template>
<style scoped>
.banner_text_container {
  position: absolute;
  width: 80%;
  z-index: 1;
  color: var(--color-white);
  gap: 20px;
  display: flex;
  flex-direction: column;
  text-shadow: var(--color-black) 1px 0 3px;
  max-width: 1660px;
  text-align: start;
  text-transform: uppercase;
}

.banner_text_container h1 {
  font-size: 5rem;
  width: 90%;
}

.banner_text_container p {
  font-size: 1rem;
  width: 50%;
}

.banner_img_container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 400px;
  overflow: hidden;
}

.banner_img_container img {
  width: 100%;
}

.banner_container {
  height: 400px;
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
}

@media screen and (max-width: 1550px) {
  .banner_text_container h1 {
    font-size: 4.5rem;
    width: 90%;
  }
  .banner_img_container {
    height: 400px;
  }
}

@media screen and (max-width: 1390px) {
  .banner_text_container h1 {
    font-size: 4.1rem;
    width: 90%;
  }
  .banner_container {
    height: 400px;
  }
}

@media screen and (max-width: 1275px) {
  .banner_text_container h1 {
    font-size: 3.2rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 1rem;
    width: 70%;
  }

  .banner_img_container {
    height: 330px;
  }
  .banner_container {
    height: 330px;
  }
}

@media screen and (max-width: 1000px) {
  .banner_text_container h1 {
    font-size: 2.8rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.8rem;
    width: 70%;
  }

  .banner_img_container {
    height: 300px;
  }
  .banner_container {
    height: 300px;
  }
}

@media screen and (max-width: 880px) {
  .banner_text_container h1 {
    font-size: 2.2rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.8rem;
    width: 70%;
  }
  .banner_img_container {
    height: 300px;
  }
  .banner_container {
    height: 300px;
  }
}
@media screen and (max-width: 700px) {
  .banner_text_container h1 {
    font-size: 1.8rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.7rem;
    width: 80%;
  }
  .banner_text_container {
    gap: 10px;
  }
  .banner_img_container {
    height: 280px;
  }
  .banner_container {
    height: 280px;
  }
}

@media screen and (max-width: 570px) {
  .banner_text_container h1 {
    font-size: 1.5rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.6rem;
    width: 80%;
  }
  .banner_img_container {
    height: 230px;
  }
  .banner_container {
    height: 230px;
  }
}
@media screen and (max-width: 470px) {
  .banner_text_container h1 {
    font-size: 1.2rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.5rem;
    width: 80%;
  }

  .banner_img_container {
    height: 180px;
  }
  .banner_container {
    height: 180px;
  }
}

@media screen and (max-width: 390px) {
  .banner_text_container h1 {
    font-size: 1rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.4rem;
    width: 80%;
  }
  .banner_img_container {
    height: 160px;
  }
  .banner_container {
    height: 160px;
  }
}
@media screen and (max-width: 315px) {
  .banner_text_container h1 {
    font-size: 0.8rem;
    width: 90%;
  }
  .banner_text_container p {
    font-size: 0.3rem;
    width: 80%;
  }
  .banner_img_container {
    height: 120px;
  }
  .banner_container {
    height: 120px;
  }
}
</style>

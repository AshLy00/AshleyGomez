<script setup></script>

<template>
  <div class="hero_about">
    <img
      class="img_1"
      src="https://tinypic.host/images/2024/03/17/U4ntitled-1-01.png"
      alt=""
    />
    <img
      class="img_2"
      src="https://tinypic.host/images/2024/03/17/banner-about-01-1.png"
      alt=""
    />
  </div>
  <div class="about_info">
    <div class="name">
      <h1 class="front">ASHLEY GÓMEZ</h1>
      <h1 class="back">ASHLEY GÓMEZ</h1>
    </div>

    <p class="work">DESIGNER | Illustrator <br /></p>

    <p>
      I am passionate about graphic design and illustration. I believe in
      importance of transforming ideas into reality to make the world a better
      place, where everyone can see their dreams come to true. I'm here to turn
      your ideas into reality. <br /><br />Let's discover the creative world
      together and make your ideas take shape! <br />
    </p>
  </div>
</template>

<style scoped>
.name {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.name h1 {
  font-size: 5rem;
}
.name .front {
  z-index: 1;
  color: var(--color-pink);
}
.name .back {
  color: white;
  -webkit-text-stroke: 20px white;
  position: absolute;
  top: 5px;
}
.about_info .work {
  text-align: center;
}
.img_1 {
  display: block;
}
.img_2 {
  display: none;
}
.hero_about img {
  width: 100%;
}
.hero_about {
  width: 100%;
  overflow: hidden;
  height: 400px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.about_info p {
  width: 50%;
}
.about_info {
  justify-content: center;
  display: flex;
  flex-direction: column;
  text-align: justify;
  align-items: center;
  text-transform: uppercase;
  gap: 20px;
  height: 160px;
  margin-bottom: 150px;
  margin-top: 10px;
}

@media screen and (max-width: 1560px) {
  .img_1 {
    display: none;
  }
  .img_2 {
    display: flex;
  }
  .about_info p {
    width: 60%;
  }
  .about_info {
    gap: 20px;
    margin-bottom: 150px;
    margin-top: 20px;
  }
}
@media screen and (max-width: 1240px) {
}
.about_info {
  margin-bottom: 100px;
  margin-top: 30px;
}
.name h1 {
  font-size: 4rem;
}

@media screen and (max-width: 1020px) {
  .hero_about {
    height: 400px;
  }
  .about_info p {
    width: 70%;
  }
}

@media screen and (max-width: 820px) {
  .hero_about {
    height: 300px;
  }
  .about_info p {
    width: 70%;
    font-size: 0.8rem;
  }
  .about_info {
    margin-bottom: 100px;
    margin-top: 10px;
  }
  .name h1 {
    font-size: 3rem;
  }
}
@media screen and (max-width: 800px) {
  .about_info {
    margin-bottom: 100px;
    margin-top: 20px;
  }
  .name h1 {
    font-size: 3rem;
  }
  .hero_about {
    height: 280px;
  }
}

@media screen and (max-width: 600px) {
  .img_1 {
    display: none;
  }
  .img_2 {
    display: flex;
  }
  .hero_about {
    height: 220px;
  }
  .name .back {
    -webkit-text-stroke: 25px white;
  }
}
@media screen and (max-width: 560px) {
  .hero_about {
    height: 180px;
  }
  .about_info p {
    font-size: 0.7rem;
    width: 65%;
  }

  .about_info {
    margin-bottom: 80px;
    margin-top: 20px;
  }
  .name h1 {
    font-size: 2rem;
  }
}

@media screen and (max-width: 400px) {
  .hero_about {
    height: 160px;
  }

  .about_info p {
    font-size: 0.6rem;
    width: 70%;
  }

  .about_info {
    margin-bottom: 60px;
    margin-top: 10px;
  }
  .name h1 {
    font-size: 1.7rem;
  }
}

@media screen and (max-width: 380px) {
  .about_info {
    margin-bottom: 60px;
    margin-top: 20px;
  }
  .hero_about {
    height: 140px;
  }
}

@media screen and (max-width: 330px) {
  .about_info {
    margin-bottom: 70px;
    margin-top: 30px;
  }
}
</style>

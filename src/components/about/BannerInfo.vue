<script setup></script>

<template>
  <div class="hero_about">
    <img
      class="img_1"
      src="https://drive.google.com/uc?export=view&id=1xndZsuZB7W2NaGhN4qrDsAh4D_bpcNMK"
      alt=""
    />
    <img
      class="img_2"
      src="https://drive.google.com/uc?export=view&id=1YkTJ8F3BycnXimg30IN6FkhtAvCExR54"
      alt=""
    />
  </div>
  <div class="about_info">
    <h1>ASHLEY GÓMEZ</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id
      est laborum.
    </p>
  </div>
</template>

<style scoped>
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
.about_info h1 {
  font-size: 5rem;
  color: var(--color-pink);
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
  margin-bottom: 100px;
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
}

@media screen and (max-width: 1020px) {
  .hero_about {
    height: 400px;
  }
  .about_info p {
    width: 70%;
  }
  .about_info h1 {
    font-size: 4.5rem;
  }
}

@media screen and (max-width: 820px) {
  .hero_about {
    height: 300px;
  }
  .about_info h1 {
    font-size: 3rem;
  }
  .about_info p {
    width: 70%;
    font-size: 0.8rem;
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
    height: 280px;
  }
}
@media screen and (max-width: 560px) {
  .hero_about {
    height: 200px;
  }
  .about_info h1 {
    font-size: 2.2rem;
  }
  .about_info p {
    font-size: 0.6rem;
    width: 65%;
  }
}

@media screen and (max-width: 400px) {
  .hero_about {
    height: 140px;
  }

  .about_info h1 {
    font-size: 1.5rem;
  }
  .about_info p {
    font-size: 0.5rem;
    width: 70%;
  }
}
</style>

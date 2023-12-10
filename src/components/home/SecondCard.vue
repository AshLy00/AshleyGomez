<script setup>
defineProps(["imageSrc", "title", "description"]);
</script>

<template>
  <div class="card_container">
    <div class="img_container">
      <img :src="imageSrc" />
    </div>

    <div class="text">
      <h1>{{ title }}</h1>
      <p>
        {{ description }}
      </p>
    </div>
  </div>
</template>
<style scoped>
.card_container img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.card_container {
  display: flex;
  text-transform: uppercase;
  gap: 20px;
  justify-content: center;
  align-items: center;
  flex-direction: row-reverse;
  width: 100%;
  justify-content: space-between;
}
.text {
  display: flex;
  text-align: start;
  flex-direction: column;
  align-items: start;
  gap: 10px;
}

.text h1 {
  font-size: 4rem;
  width: 70%;
  color: var(--color-darkblue);
}

.text p {
  font-size: 1.5rem;
  width: 60%;
}

.img_container {
  width: 500px;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  border-radius: 20px;
}

@media screen and (max-width: 2300px) {
  .text h1 {
    font-size: 4rem;
    width: 80%;
  }

  .text p {
    font-size: 1.5rem;
    width: 80%;
  }
}

@media screen and (max-width: 1550px) {
  .text h1 {
    font-size: 3.5rem;
    width: 80%;
  }

  .text p {
    font-size: 1.2rem;
    width: 80%;
  }

  .img_container {
    width: 450px;
    height: 450px;
  }
}

@media screen and (max-width: 1370px) {
  .text h1 {
    font-size: 3.5rem;
    width: 90%;
  }
}

@media screen and (max-width: 1275px) {
  .text h1 {
    font-size: 3rem;
    width: 80%;
  }
  .text p {
    font-size: 1rem;
    width: 70%;
  }

  .img_container {
    width: 380px;
    height: 380px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 1070px) {
  .text h1 {
    font-size: 2.5rem;
    width: 80%;
  }
  .text p {
    font-size: 0.8rem;
    width: 70%;
  }

  .img_container {
    width: 320px;
    height: 320px;
  }
  .card_container {
    gap: 20px;
  }
}
@media screen and (max-width: 930px) {
  .text h1 {
    font-size: 2.1rem;
    width: 70%;
  }
  .text p {
    font-size: 0.7rem;
    width: 70%;
  }

  .img_container {
    width: 250px;
    height: 250px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 820px) {
  .text h1 {
    font-size: 1.7rem;
    width: 70%;
  }
  .text p {
    font-size: 0.7rem;
    width: 70%;
  }

  .img_container {
    width: 200px;
    height: 200px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 747px) {
  .text h1 {
    font-size: 1.5rem;
    width: 70%;
  }
  .text p {
    font-size: 0.6rem;
    width: 80%;
  }

  .img_container {
    width: 180px;
    height: 180px;
  }
  .card_container {
    gap: 20px;
  }
}
@media screen and (max-width: 686px) {
  .text h1 {
    font-size: 1.5rem;
    width: 70%;
  }
  .text p {
    font-size: 0.5rem;
    width: 80%;
  }

  .img_container {
    width: 170px;
    height: 170px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 579px) {
  .text h1 {
    font-size: 1.3rem;
    width: 90%;
  }
  .text p {
    font-size: 0.4rem;
    width: 70%;
  }

  .img_container {
    width: 150px;
    height: 150px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 507px) {
  .text h1 {
    font-size: 1rem;
    width: 70%;
  }
  .text p {
    font-size: 0.4rem;
    width: 80%;
  }

  .img_container {
    width: 130px;
    height: 130px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 440px) {
  .text h1 {
    font-size: 1rem;
    width: 70%;
  }
  .text p {
    font-size: 0.4rem;
    width: 90%;
  }

  .img_container {
    width: 130px;
    height: 130px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 390px) {
  .text h1 {
    font-size: 1rem;
    width: 90%;
  }
  .text p {
    font-size: 0.4rem;
    width: 90%;
  }

  .img_container {
    width: 100px;
    height: 100px;
  }
  .card_container {
    gap: 20px;
  }
}

@media screen and (max-width: 361px) {
  .text h1 {
    font-size: 1rem;
    width: 100%;
  }
  .text p {
    display: none;
  }

  .img_container {
    width: 100px;
    height: 100px;
    border-radius: 20px;
  }
  .card_container {
    gap: 20px;
  }
}
@media screen and (max-width: 330px) {
  .text h1 {
    font-size: 0.9rem;
    width: 100%;
  }
}
@media screen and (max-width: 300px) {
  .text h1 {
    font-size: 0.8rem;
    width: 100%;
  }
}
</style>

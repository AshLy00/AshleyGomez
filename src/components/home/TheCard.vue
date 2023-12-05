<script setup></script>

<template>
  <div class="card_container">
    <div class="img_container">
      <img
        src="https://drive.google.com/uc?export=view&id=1SRmHXPyoeXfNwgXGVOo_E930g5oCO321"
        alt=""
      />
    </div>

    <div class="text">
      <h1>Lorem ipsum dolor sit.</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
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
  display: grid;
  grid-template-columns: 1fr 1fr;
  text-transform: uppercase;
  gap: 20px;
  height: 510px;
  justify-content: center;
  align-items: center;
}
.text {
  display: flex;
  text-align: end;
  flex-direction: column;
  align-items: end;
  gap: 10px;
}

.text h1 {
  font-size: 4rem;
  width: 70%;
  color: var(--color-darkblue);
}

.text p {
  font-size: 1.5rem;
  width: 90%;
}

.img_container {
  width: 500px;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  border-radius: 30px;
}

@media screen and (max-width: 2300px) {
  .text h1 {
    font-size: 4rem;
    width: 80%;
  }

  .text p {
    font-size: 1.5rem;
    width: 100%;
  }
}

@media screen and (max-width: 1550px) {
  .text h1 {
    font-size: 3.5rem;
    width: 80%;
  }

  .text p {
    font-size: 1.2rem;
    width: 100%;
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
    width: 90%;
  }
  .text p {
    font-size: 1rem;
    width: 100%;
  }

  .img_container {
    width: 380px;
    height: 380px;
  }
  .card_container {
    gap: 20px;
    height: 500px;
  }
}

@media screen and (max-width: 1070px) {
  .text h1 {
    font-size: 2.5rem;
    width: 90%;
  }
  .text p {
    font-size: 0.8rem;
    width: 90%;
  }

  .img_container {
    width: 320px;
    height: 320px;
  }
  .card_container {
    gap: 20px;
    height: 450px;
  }
}
@media screen and (max-width: 930px) {
  .text h1 {
    font-size: 2.1rem;
    width: 90%;
  }
  .text p {
    font-size: 0.7rem;
    width: 90%;
  }

  .img_container {
    width: 250px;
    height: 250px;
  }
  .card_container {
    gap: 20px;
    height: 350px;
  }
}

@media screen and (max-width: 820px) {
  .text h1 {
    font-size: 1.7rem;
    width: 90%;
  }
  .text p {
    font-size: 0.7rem;
    width: 100%;
  }

  .img_container {
    width: 200px;
    height: 200px;
  }
  .card_container {
    gap: 20px;
    height: 300px;
  }
}

@media screen and (max-width: 747px) {
  .text h1 {
    font-size: 1.5rem;
    width: 90%;
  }
  .text p {
    font-size: 0.6rem;
    width: 100%;
  }

  .img_container {
    width: 180px;
    height: 180px;
  }
  .card_container {
    gap: 20px;
    height: 300px;
  }
}
@media screen and (max-width: 686px) {
  .text h1 {
    font-size: 1.5rem;
    width: 90%;
  }
  .text p {
    font-size: 0.5rem;
    width: 100%;
  }

  .img_container {
    width: 170px;
    height: 170px;
  }
  .card_container {
    gap: 20px;
    height: 280px;
  }
}

@media screen and (max-width: 579px) {
  .text h1 {
    font-size: 1.3rem;
    width: 90%;
  }
  .text p {
    font-size: 0.4rem;
    width: 100%;
  }

  .img_container {
    width: 150px;
    height: 150px;
  }
  .card_container {
    gap: 20px;
    height: 220px;
  }
}

@media screen and (max-width: 507px) {
  .text h1 {
    font-size: 1rem;
    width: 90%;
  }
  .text p {
    font-size: 0.4rem;
    width: 110%;
  }

  .img_container {
    width: 130px;
    height: 130px;
  }
  .card_container {
    gap: 20px;
    height: 180px;
  }
}

@media screen and (max-width: 440px) {
  .text h1 {
    font-size: 1rem;
    width: 90%;
  }
  .text p {
    font-size: 0.4rem;
    width: 110%;
  }

  .img_container {
    width: 130px;
    height: 130px;
  }
  .card_container {
    gap: 20px;
    height: 180px;
  }
}

@media screen and (max-width: 390px) {
  .text h1 {
    font-size: 1rem;
    width: 90%;
  }
  .text p {
    font-size: 0.4rem;
    width: 120%;
  }

  .img_container {
    width: 100px;
    height: 100px;
  }
  .card_container {
    gap: 20px;
    height: 150px;
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
    height: 140px;
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

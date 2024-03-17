<script setup></script>
<template>
  <footer>
    <div class="footer_container">
      <a href="https://linktr.ee/SpaceBunnyBun" class="iconos_container">
        <img src="https://tinypic.host/images/2024/03/17/3333-1.png" />
      </a>
      <div class="derechos">
        <p class="text">ALL MY SOCIAL MEDIA</p>
        <p>© 2023 - ASHLEY GÓMEZ</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  justify-content: center;
  display: flex;
  align-items: center;
  background-color: black;
  color: white;
  height: 190px;
  font-size: 0.8rem;
  justify-content: center;
}
.footer_container {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
.iconos_container {
  justify-content: center;
  align-items: center;
  display: flex;
  width: 420px;
}
.iconos_container img {
  width: 50%;
}
.text {
  font-size: 0.8rem;
}
.derechos {
  justify-content: center;
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 10px;
}

@media screen and (max-width: 930px) {
  .iconos_container {
    width: 390px;
  }
  footer {
    height: 150px;
    font-size: 0.8rem;
  }
}
@media screen and (max-width: 530px) {
  .iconos_container {
    width: 300px;
  }
  footer {
    height: 140px;
    font-size: 0.5rem;
  }
  .footer_container {
    gap: 12px;
  }
  .iconos_container img {
    width: 40%;
  }
  .text {
    font-size: 0.7rem;
  }
  .derechos {
    justify-content: center;
    align-items: center;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
}
@media screen and (max-width: 400px) {
  .iconos_container {
    width: 250px;
  }
  footer {
    height: 120px;
    font-size: 0.4rem;
  }
  .footer_container {
    gap: 12px;
  }
}

@media screen and (max-width: 350px) {
  .iconos_container {
    width: 200px;
  }
  footer {
    height: 100px;
    font-size: 0.5rem;
  }
}
</style>

<script setup></script>
<template>
  <footer>
    <div class="footer_container">
      <div class="iconos_container">
        <img
          src="https://drive.google.com/uc?export=view&id=1tTzNMdsT2j75GQmDsy_66QHWLjzGo29z"
          alt=""
        />
      </div>
      <div class="derechos"><p>© 2023 - ASHLEY GÓMEZ</p></div>
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
  height: 170px;
  font-size: 1.3rem;
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
  width: 150%;
}

@media screen and (max-width: 930px) {
  .iconos_container {
    width: 380px;
  }
  footer {
    height: 150px;
    font-size: 1.2rem;
  }
}
@media screen and (max-width: 530px) {
  .iconos_container {
    width: 300px;
  }
  footer {
    height: 120px;
    font-size: 1rem;
  }
  .footer_container {
    gap: 12px;
  }
}
@media screen and (max-width: 400px) {
  .iconos_container {
    width: 250px;
  }
  footer {
    height: 100px;
    font-size: 0.7rem;
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
    height: 80px;
    font-size: 0.6rem;
  }
}
</style>

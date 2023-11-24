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
  height: 120px;
}
.footer_container {
  width: 80%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
.iconos_container img {
  width: 100%;
}

@media screen and (max-width: 900px) {
}
</style>

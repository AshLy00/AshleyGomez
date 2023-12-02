<script setup></script>

<template>
  <section class="intro_container">
    <img
      src="https://drive.google.com/uc?export=view&id=1qDrPfFgTBCpkrSp1juT4Dmh8Ggxp_-95"
      alt=""
    />
    <div class="intro_text_container">
      <h1>PORTAFOLIO</h1>
    </div>
  </section>
</template>

<style scoped>
.intro_container {
  width: 100%;
  height: 400px;
  overflow: hidden;
  position: relative;
  display: flex;
  align-items: center;
}
.intro_container img {
  width: 100%;
}
.intro_text_container {
  position: absolute;

  color: var(--color-white);
  width: 100%;
  text-align: center;
}

.intro_text_container h1 {
  font-size: 1000%;
  text-shadow: var(--color-black) 1px 0 10px;
}

@media screen and (max-width: 1580px) {
  .intro_text_container h1 {
    font-size: 900%;
  }
  .intro_container {
    height: 300px;
  }
}

@media screen and (max-width: 1410px) {
  .intro_text_container h1 {
    font-size: 800%;
  }
}
@media screen and (max-width: 1260px) {
  .intro_text_container h1 {
    font-size: 700%;
  }
}

@media screen and (max-width: 1090px) {
  .intro_text_container h1 {
    font-size: 600%;
  }
}

@media screen and (max-width: 900px) {
  .intro_text_container h1 {
    font-size: 500%;
  }

  .intro_container {
    height: 200px;
  }
}
@media screen and (max-width: 790px) {
  .intro_text_container h1 {
    font-size: 400%;
  }
}
@media screen and (max-width: 640px) {
  .intro_text_container h1 {
    font-size: 300%;
  }
  .intro_container {
    height: 150px;
  }
}

@media screen and (max-width: 460px) {
  .intro_text_container h1 {
    font-size: 200%;
  }

  .intro_container {
    height: 100px;
  }
}

@media screen and (max-width: 310px) {
  .intro_text_container h1 {
    font-size: 150%;
  }

  .intro_container {
    height: 80px;
  }
}
</style>

<script setup>
import TheCard from "./TheCard.vue";
import SecondCard from "./SecondCard.vue";
</script>

<template>
  <section class="showcase">
    <TheCard
      imageSrc="https://firebasestorage.googleapis.com/v0/b/ashley-portafolio.appspot.com/o/015.jpg?alt=media&token=0f421d29-3a9c-47dd-84fb-0cac06f5bc6e"
      title="MIMOS"
      description="THE BEST OF MIMOS WITH A LITTLE OF MY SPARKLE"
    />
    <SecondCard
      imageSrc="https://firebasestorage.googleapis.com/v0/b/ashley-portafolio.appspot.com/o/026.PNG?alt=media&token=cafa8efd-631e-4c2f-9d5b-df7ba40f3166"
      title="CROYDON"
      description="WEBSITE IDEA FOR CROYDON"
    />
  </section>
</template>
<style scoped>
section {
  width: 60%;
  display: flex;
  flex-direction: column;
  gap: 70px;
  margin-top: 70px;
  margin-bottom: 70px;
}

@media screen and (max-width: 2300px) {
  section {
    width: 70%;
  }
}

@media screen and (max-width: 1770px) {
  section {
    width: 80%;
  }
}
@media screen and (max-width: 1550px) {
  section {
    width: 80%;
  }
}

@media screen and (max-width: 930px) {
  section {
    width: 80%;
    gap: 50px;
    margin-top: 50px;
    margin-bottom: 50px;
  }
}
@media screen and (max-width: 747px) {
  section {
    width: 75%;
  }
}

@media screen and (max-width: 505px) {
  section {
    width: 80%;
    gap: 30px;
    margin-top: 30px;
    margin-bottom: 30px;
  }
}
@media screen and (max-width: 420px) {
  section {
    width: 80%;
  }
}
</style>

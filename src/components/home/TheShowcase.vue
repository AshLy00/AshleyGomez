<script setup>
import TheCard from "./TheCard.vue";
import SecondCard from "./SecondCard.vue";
</script>

<template>
  <section class="showcase">
    <TheCard
      imageSrc="https://tinypic.host/images/2024/03/17/406472923_122111667968108389_2621784756347966090_n-1.jpeg"
      title="MIMOS"
      description="THE BEST OF MIMOS WITH A LITTLE OF MY SPARKLE"
    />
    <SecondCard
      imageSrc="https://tinypic.host/images/2024/03/17/Captur222a.png"
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

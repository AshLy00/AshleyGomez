<script setup>
import TheCard from "./TheCard.vue";
</script>

<template>
  <section class="showcase">
    <TheCard />
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

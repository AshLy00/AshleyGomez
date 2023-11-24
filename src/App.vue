<script setup>
import { RouterView } from "vue-router";
import TheHeader from "./components/app/TheHeader.vue";
import TheFooter from "./components/app/TheFooter.vue";
</script>

<template>
  <TheHeader />
  <main>
    <RouterView />
  </main>
  <TheFooter />
</template>

<style scoped></style>

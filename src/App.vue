<script setup>
import { RouterView } from "vue-router";
import TheHeader from "./components/templates/TheHeader.vue";
import TheFooter from "./components/templates/TheFooter.vue";
</script>

<template>
  <TheHeader />
  <main>
    <RouterView />
  </main>
  <TheFooter />
</template>

<style scoped></style>

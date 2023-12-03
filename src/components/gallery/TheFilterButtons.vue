<script setup>
import { useRouter } from "vue-router";

const router = useRouter();
const props = defineProps({
  category: String,
});
</script>
<template>
  <div
    @click="() => router.push({ name: 'gallery', params: { id: category } })"
    class="single_filter"
    :style="`background-color: var(--color-${category})`"
  >
    <p>{{ category }}</p>
  </div>
</template>

<style scoped>
.single_filter {
  background-color: var(--color-pink);
  height: 50px;
  width: 250px;
  align-items: center;
  display: flex;
  justify-content: center;
  border-radius: 30px;
  color: var(--color-white);
  font-size: 0.9rem;
  text-transform: uppercase;
  cursor: pointer;
}
</style>

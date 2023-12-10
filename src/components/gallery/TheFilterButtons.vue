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
  width: 210px;
  align-items: center;
  display: flex;
  justify-content: center;
  border-radius: 30px;
  color: var(--color-white);
  font-size: 0.9rem;
  text-transform: uppercase;
  cursor: pointer;
  max-width: 1080px;
}

@media screen and (max-width: 1220px) {
  .single_filter {
    height: 50px;
    width: 180px;
    border-radius: 30px;
    font-size: 0.9rem;
  }
}
@media screen and (max-width: 1080px) {
  .single_filter {
    height: 45px;
    width: 140px;
    border-radius: 30px;
    font-size: 0.8rem;
  }
}
@media screen and (max-width: 850px) {
  .single_filter {
    height: 45px;
    width: 150px;
    border-radius: 30px;
    font-size: 0.7rem;
  }
}
@media screen and (max-width: 730px) {
  .single_filter {
    height: 50px;
    width: 134px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}

@media screen and (max-width: 530px) {
  .single_filter {
    height: 50px;
    width: 120px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}

@media screen and (max-width: 460px) {
  .single_filter {
    height: 50px;
    width: 100px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}
@media screen and (max-width: 400px) {
  .single_filter {
    height: 40px;
    width: 90px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}

@media screen and (max-width: 370px) {
  .single_filter {
    height: 40px;
    width: 90px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}

@media screen and (max-width: 340px) {
  .single_filter {
    height: 40px;
    width: 120px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}

@media screen and (max-width: 310px) {
  .single_filter {
    height: 40px;
    width: 110px;
    border-radius: 30px;
    font-size: 0.6rem;
  }
}
</style>

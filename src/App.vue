<script setup>
import HelloWorld from './components/boton.vue';
</script>

<template>
  <div class="header">
    <h1>Ashley Gómez</h1>
    <div class="botones">
      <p>Projects</p>
      <p>About</p>
    </div>
  </div>
</template>

<style scoped>
h1{
  font-family: 'Rowdies', sans-serif;
  font-size: 2.5rem;
}
p {
  font-family: 'Aoboshi One', serif;
}
.header
{
  display: flex;
  justify-content: space-between;
  margin: 40px;
  margin-right: 80px;
  margin-left: 80px;
  align-items: center;
}
.botones
{
  display: flex;
}

.botones p{
  margin: 20px;
  padding: 10px;
  border: solid;
  border-radius: 30px;
  width: 120px;
  text-align:center;
}
</style>

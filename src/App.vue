<script setup>
import HelloWorld from './components/boton.vue';
</script>

<template>
  <header>
  <div class="header_items">
    <h1>Ashley Gómez</h1>
    <div class="botones">
      <p>Projects</p>
      <p>About</p>
    </div>
  </div>
  </header>
</template>

<style scoped>
header{
  width:100%;
  background-color: red;
}
h1{
  font-family: 'Rowdies', sans-serif;
  font-size: 2.5rem;
}
p {
  font-family: 'Aoboshi One', serif;
}
.header_items
{
  padding: 20px;
  display:flex;
  margin-right: 80px;
  margin-left: 80px;
  justify-content: space-between;
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

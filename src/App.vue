<script setup>
import HelloWorld from './components/boton.vue';
</script>

<template>
  <header>
  <div class="header_items">
    <h1>ASHLEY GÓMEZ</h1>
    <div class="botones">
      <button>PROJECTS</button>
      <button>ABOUT</button>
    </div>
  </div>
  </header>
</template>

<style scoped>
header{
  width:100%;
  background-color: #6DB3E6;
  color: white;
}

h1{
  font-family: 'Rowdies', sans-serif;
  font-size: 2rem;
}

button {
  font-family: 'Aoboshi One', serif;
  color: white;
  background-color:#6DB3E6;
  font-size: 0.8rem;
}

.header_items
{
  padding: 30px;
  display:flex;
  margin-right: 80px;
  margin-left: 80px;
  justify-content: space-between;
  align-items: center;
}

.botones button{
  margin: 20px;
  padding: 10px;
  border: solid;
  border-radius: 30px;
  width: 140px;
  text-align:center;
}
</style>

@media

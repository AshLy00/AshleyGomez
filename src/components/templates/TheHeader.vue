<script setup></script>

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
header {
  width: 100%;
  background-color: var(--color-blue);
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 110px;
}

.header_items {
  width: 80%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 15px;
}

.botones {
  display: flex;
  gap: 15px;
}

@media screen and (max-width: 900px) {
  header {
    color: var(--color-white);
    height: 140px;
  }

  .header_items {
    flex-direction: column;
  }
}
</style>

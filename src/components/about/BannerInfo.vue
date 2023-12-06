<script setup></script>

<template>
  <div class="hero_about">
    <img
      src="https://drive.google.com/uc?export=view&id=1iOCvE6nghCS8ais4KSrpWln2WswNNmla"
      alt=""
    />
  </div>
  <div class="about_info">
    <h1>ASHLEY GÓMEZ</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id
      est laborum.
    </p>
  </div>
</template>

<style scoped>
.hero_about img {
  width: 100%;
}
.hero_about {
  width: 100%;
  overflow: hidden;
  height: 500px;
  justify-content: center;
  align-items: center;
  display: flex;
}
.about_info h1 {
  font-size: 5rem;
  color: var(--color-pink);
}
.about_info p {
  width: 50%;
}
.about_info {
  justify-content: center;
  display: flex;
  flex-direction: column;
  text-align: justify;
  align-items: center;
  text-transform: uppercase;
  gap: 20px;
  height: 160px;
  margin-bottom: 100px;
}
</style>

<script setup></script>

<template>
  <div class="software_skills_container">
    <h1>SOFTWARE SKILLS</h1>
    <div class="all_images">
      <div class="img_container">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Adobe_Illustrator_CC_icon.svg/2101px-Adobe_Illustrator_CC_icon.svg.png"
          alt=""
        />
      </div>

      <div class="img_container">
        <img
          src="https://drive.google.com/uc?export=view&id=1Z5G54Ey5do00BNybb1KtbySmhL2Diny3"
          alt=""
        />
      </div>

      <div class="img_container">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Adobe_Premiere_Pro_CC_icon.svg/2101px-Adobe_Premiere_Pro_CC_icon.svg.png"
          alt=""
        />
      </div>
      <div class="text1">
        <p>ILUSTRATOR</p>
        <p>AFTER EFFECTS</p>
        <p>PREMIER PRO</p>
      </div>
      <div class="img_container">
        <img
          src="https://drive.google.com/uc?export=view&id=1oEI-TPsjho5kXfGHh4pnP9BHO9rW4ega"
          alt=""
        />
      </div>

      <div class="img_container">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png"
          alt=""
        />
      </div>

      <div class="img_container">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Adobe_Photoshop_CC_icon.svg/2101px-Adobe_Photoshop_CC_icon.svg.png"
          alt=""
        />
      </div>
      <div class="text2">
        <p>MAYA</p>
        <p>VISUAL STUDIO</p>
        <p>PHOTOSHOP</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.names {
  display: flex;
  gap: 15px;
  justify-content: center;
  text-align: center;
}
.names p {
  width: 150px;
}
.software_skills_container h1 {
  color: var(--color-purple);
  font-size: 3rem;
}
.software_skills_container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  flex-direction: column;
  margin-top: 50px;
}
.img_container {
  width: 150px;
  height: 150px;
  overflow: hidden;
}
.img_container img {
  width: 100%;
}
.all_images {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  gap: 15px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: 1fr;
}
.text2 {
  grid-column: 1/4;
  grid-row: 4 / 5;
  display: flex;
  justify-content: center;
  gap: 60px;
  text-align: center;
  margin-left: 40px;
}
.text1 {
  grid-column: 1/4;
  grid-row: 2 / 3;
  display: flex;
  justify-content: center;
  gap: 40px;
}

@media screen and (max-width: 850px) {
  .software_skills_container h1 {
    font-size: 2rem;
  }
  p {
    font-size: 0.8rem;
  }
  .img_container {
    width: 100px;
    height: 100px;
    overflow: hidden;
  }
  .text2 {
    gap: 50px;
    margin-left: 20px;
  }
  .software_skills_container {
    gap: 20px;
    margin-top: 10px;
  }
}

@media screen and (max-width: 560px) {
  .software_skills_container h1 {
    font-size: 1.5rem;
  }
  p {
    font-size: 0.6rem;
  }
  .img_container {
    width: 80px;
    height: 80px;
    overflow: hidden;
  }
  .text2 {
    gap: 50px;
    margin-left: 20px;
  }
  .software_skills_container {
    gap: 20px;
    margin-top: 0px;
  }
}

@media screen and (max-width: 400px) {
  .software_skills_container h1 {
    font-size: 1.3rem;
  }
  p {
    font-size: 0.5rem;
  }
  .img_container {
    width: 60px;
    height: 60px;
    overflow: hidden;
  }
  .text2 {
    gap: 40px;
    margin-left: 0px;
  }
  .software_skills_container {
    gap: 20px;
    margin-top: 0px;
  }
}
</style>

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
    </div>
    <div class="names">
      <p>ILUSTRATOR</p>
      <p>AFTER EFFECTS</p>
      <p>PREMIER PRO</p>
      <p>MAYA</p>
      <p>VISUAL STUDIO</p>
      <p>PHOTOSHOP</p>
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
  gap: 15px;
}
</style>

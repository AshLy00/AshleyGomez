<script setup>
import TheGalleryItem from './TheGalleryItem.vue';
</script>
<template>
<div class="gallery_grid">
<TheGalleryItem />
<TheGalleryItem />
<TheGalleryItem />
<TheGalleryItem />
<TheGalleryItem />
</div>
</template>


<style scoped>
.gallery_grid{
    display: grid;
grid-template-columns: 1fr 1fr 1fr 1fr;
gap:20px;
margin-top: 50px;
margin-bottom: 50px;
}
</style>
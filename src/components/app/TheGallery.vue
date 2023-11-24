<script setup>
import TheGalleryItem from './TheGalleryItem.vue';
import TheFilterButtons from './TheFilterButtons.vue';
</script>
<template>
    <div class="filters_buttons">
        <TheFilterButtons />
        <TheFilterButtons />
        <TheFilterButtons />
        <TheFilterButtons />
        <TheFilterButtons />
    </div>
<div class="gallery_grid">
<TheGalleryItem />
<TheGalleryItem />
<TheGalleryItem />
<TheGalleryItem />
<TheGalleryItem />
</div>
</template>


<style scoped>
.filters_buttons{
    display: flex;
    gap: 20px;
    height: 100px;
    align-items: center;
    justify-content: center;
}
.gallery_grid{
    display: grid;
grid-template-columns: 1fr 1fr 1fr 1fr;
gap:20px;
margin-top: 20px;
margin-bottom: 50px;
}
</style>
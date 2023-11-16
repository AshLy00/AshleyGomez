<script setup></script>

<template>
    <div class="banner_container">
        <div class="banner_text_container">
            <h1>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT</h1>
            <p>LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING ELIT
                LOREM IPSUM DOLOR SIT AMET CONSECTETUR ADIPISCING</p>
        </div>
        <div class="banner_img_container">
            <img src="https://drive.google.com/uc?export=view&id=1pKPhvwj9zK2DfHTCy5rbUxRcQDnUoh3X" alt="">
        </div>
    </div>
</template>
<style scoped>
.banner_text_container {
    position: absolute;
    z-index: 1;
    color: var(--color-white);
    gap: 20px;
    display: flex;
    flex-direction: column;
    text-shadow: var(--color-black) 1px 0 3px;
    max-width: 1660px;
    text-align: center;
    align-items: center;
    display: none;
}

.banner_text_container h1 {
    font-size: 5rem;
    width: 90%;
}

.banner_text_container p {
    font-size: 1rem;
    width: 50%;
}

.banner_img_container {
    display: flex;
    justify-content: center;
    align-items: start;
    width: 100%;
    height: 500px;
    overflow: hidden;
}

.banner_img_container img {
    width: 100%;
}

.banner_container {
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
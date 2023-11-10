<script setup></script>

<template>
    <div class="all_container">
        <div class="img_container">
            <img src="https://drive.google.com/uc?export=view&id=1QSSDKznHfjA3SSck9Y62Kn_YJ5uOqZNL" alt="">
        </div>
        <div class="text_container">
            <h1>NOMBRE</h1>
        </div>
    </div>
</template>
<style scoped>
.all_container {
    display: flex;
    justify-content: center;
    align-items: center;
}
.img_container {
    width: 320px;
    border-radius: 30px;
    overflow: hidden;
}

.img_container img {
    width: 100%;
}

.text_container {
    position: absolute;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: var(--color-white);
    text-shadow: var(--color-black) 1px 0 3px;
}


</style>

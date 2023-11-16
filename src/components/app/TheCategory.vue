<script setup></script>

<template>
    <div class="all_container">
        <div class="img_container">
            <img src="https://drive.google.com/uc?export=view&id=1Qlyq0mFIL3XzSjw73HmFEgAH87NKuUms" alt="">
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
    display: flex;
    justify-content: center;
    align-items: center;
    color: var(--color-white);
    text-shadow: var(--color-black) 1px 0 3px;
}

@media screen and (max-width: 1580px) {
    .img_container {
        width: 280px;
    }
}

@media screen and (max-width: 1400px) {
    .img_container {
        width: 220px;
    }
}

@media screen and (max-width: 1100px) {
    .img_container {
        width: 180px;
    }
}

@media screen and (max-width: 1000px) {
    .img_container {
        width: 580px;
        height: 100px;
        display: flex;
        align-items: center;
    }
}

@media screen and (max-width: 740px) {
    .img_container {
        width: 250px;
        height: 80px;
        display: flex;
        align-items: center;
    }

    .text_container h1 {
        font-size: 0.8rem;
    }
}

@media screen and (max-width: 580px) {
    .img_container {
        width: 200px;
        height: 80px;
        display: flex;
        align-items: center;
    }

    .text_container h1 {
        font-size: 0.8rem;
    }
}
</style>

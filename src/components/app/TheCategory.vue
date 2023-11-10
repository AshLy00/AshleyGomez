<script setup></script>

<template>
<div class="all_container">
    <div class="img_container">
        <img src="emojis.png" />
    </div>
    <div class="text_container">
        <h1>NOMBRE</h1>
    </div>
    
</div>
</template>
<style scoped>
.img_container{
    width: 320px;
    border-radius: 20px;
    overflow: hidden;
}
.img_container img{
    width:100%
}
.text_container{
    position: absolute;
    top:45%;
    left:25%;
}
.all_container{
    position: relative;
    display: flex   ;
    justify-content: center;
}
</style>

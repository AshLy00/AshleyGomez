<script setup>
import TheCard from './TheCard.vue';
</script>

<template>
    <section class="showcase">
        <TheCard />
        <TheCard />
        <TheCard />
    </section>

</template>
<style scoped>
section{
    width: 60%;
}

@media screen and (max-width: 2300px) {
    section{
    width: 70%;
}
}

@media screen and (max-width: 1770px) {
    section{
    width: 80%;
}

}
@media screen and (max-width: 1550px) {
    section{
    width: 80%;
}
}
@media screen and (max-width: 747px) {
    section{
    width: 75%;
}
}
@media screen and (max-width: 420px) {
    section{
    width: 80%;
}
}
</style>

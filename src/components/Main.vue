<script>
import Card from './Card.vue';
import SlideImage from './SlideImage.vue';

export default {
    name:'Main',
    components: {
        Card,
        SlideImage
    }
}
</script>

<template>
    <div class="slider-image">
        <SlideImage />
    </div>
    <div class="main-container">
        <Card />
    </div>
</template>

<style scoped>
.main-container {
    background-color: rgb(238, 236, 233);
    display: flex;
    position: relative;
}
</style>
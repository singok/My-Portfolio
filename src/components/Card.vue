<script>
import ClickButton from './ClickButton.vue';

export default {
    name:'Card',
    components: {
        ClickButton
    }
}
</script>

<template>
    <div class="card-layout">
        <div class="card-image">
            <img src="/images/slider_images/slider1.jpg" alt="Card Image"/>
        </div>
        <div class="card-body">
            <p class="card-paragraph">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled</p>
        </div>
        <div class="card-footer">
            <ClickButton />
        </div>
    </div>
</template>

<style scoped>
.card-layout {
    display: flex;
    flex-direction: column;
    box-shadow: rgba(37, 38, 39, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 1px 3px 1px;
    width: 22%;
}
.card-image img{
    width: 100%;
    object-fit: cover;
}
.card-paragraph {
    padding: 0.5rem 1rem;
    text-align: justify;
    font-size: 16px;
}
.card-footer {
    display: flex;
    justify-content: end;
    padding: 0.5rem 1rem;
}
</style>
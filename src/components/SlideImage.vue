<script>
export default {
    name: "SlideImage",
}
</script>

<template>
<swiper-container class="swiper" :spaceBetween="30" :centeredSlides="true" :autoplay="{
      delay: 3000,
      disableOnInteraction: false,
    }" :speed="1200" :pagination="{
      clickable: true,
    }" :navigation="true">
    <swiper-slide><img src="/images/slider_images/slider1.jpg" /></swiper-slide>
    <swiper-slide><img src="/images/slider_images/slider2.jpg" /></swiper-slide>
    <swiper-slide><img src="/images/slider_images/slider3.jpg" /></swiper-slide>
    <swiper-slide><img src="/images/slider_images/slider4.jpg" /></swiper-slide>
</swiper-container>
</template>

<style scoped>
.swiper {
    width: 100%;
}

swiper-slide {
    text-align: center;
    font-size: 18px;
    background: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
}

swiper-slide img {
    display: block;
    width: 100%;
    height: 40rem;
    object-fit: cover;
}
</style>

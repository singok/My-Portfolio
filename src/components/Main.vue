<script>
import Card from './Card.vue';
import SlideImage from './SlideImage.vue';
import Heading from './Heading.vue';
import Skill from './Skill.vue';
import Address from './Address.vue';
import ContactForm from './ContactForm.vue';

export default {
    name:'Main',
    components: {
        Card,
        SlideImage,
        Heading,
        Skill,
        Address,
        ContactForm
    }
}
</script>

<template>
    <div class="slider-image">
        <SlideImage />
    </div>
    <div class="main-container">
        <div class="my-skills">
            <Heading name="Skills" />
            <div class="skill-section">
                <Skill />
                <Skill />
                <Skill />
                <Skill />
                <Skill />
            </div>
        </div>
        <div class="my-projects">
            <Heading name="Projects" />
            <div class="card-section">
                <Card />
                <Card />
                <Card />
                <Card />
            </div>
        </div>
        <div class="contact-me">
            <Heading name="Contact" />
            <div class="contact-section">
                <div class="address-part"><Address /></div>
                <div class="contact-part"><ContactForm /></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.main-container {
    background-color: rgb(238, 236, 233);
    display: flex;
    flex-direction: column;
    gap: 3rem;
    padding: 2rem 5rem;
    background-color: white;
}
.my-projects, .my-skills, .contact-me {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}
.card-section {
    display: flex;
    gap: 2rem;
    justify-content: space-between;
    flex-wrap: wrap;
}
.skill-section {
    display: flex;
    gap: 2rem;
    justify-content: space-evenly;
    flex-wrap: wrap;
}
.contact-section {
    display: flex;
    box-shadow: rgba(37, 38, 39, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 1px 3px 1px;
}
.address-part, .contact-part {
    padding: 2rem 3rem;
    width: 50%;
}
</style>
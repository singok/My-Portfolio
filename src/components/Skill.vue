<script>
export default {
    name: 'Skill'
}
</script>

<template>
<div class="skill-layout">
    <div class="icon-image">
        <font-awesome-icon :icon="['fas', 'user-secret']" size="7x" />
    </div>
    <div class="icon-desc">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled.</div>
</div>
</template>

<style scoped>
.skill-layout {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    width: 25%;
    text-align: center;
}
</style>

<script>
export default {
    name:"Heading",
    props: {
        name:String
    }
}
</script>

<template>
    <div class="heading">
        <h1>{{ name }}</h1>
    </div>
</template>

<style scoped>
.heading h1 {
    text-align: center;
    font-weight: bold;
    text-transform: uppercase;
    text-decoration: underline;
    font-size: 25px;
}
</style>
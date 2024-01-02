<script>
export default {
    name:'Address'
}
</script>

<template>
    <div class="address">
        <label>Name : John Cena</label>
        <label>Phone No. : 98########</label>
        <label>Email Address : john.cena@gmail.com</label>
        <label>Address : Kathmandu, Nepal</label>
    </div>
</template>

<style scoped>
.address {
    display: flex;
    flex-direction: column;
    gap:1rem;
}
</style>
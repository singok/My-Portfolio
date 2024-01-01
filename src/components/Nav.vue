<script>
export default {
    name:'Nav'
}
</script>

<template>  
    <nav class="nav">
        <div class="logo">
            logo
        </div>
        <div class="nav-item">
            <ul>
                <li>home</li>
                <li>projects</li>
                <li>contact</li>
                <li>about me</li>
            </ul>
        </div>
    </nav>
</template>

<style scoped>
.nav {
    display: flex;
    justify-content: space-between;
    background-color: black;
    color: white;
    line-height: 2rem;
}

.logo {
    text-transform: uppercase;
    font-weight: bold;
}

.nav-item ul {
    display: flex;
    gap: 3rem;
    text-transform: capitalize;
    list-style: none;
}

.nav-item, .logo {
    padding: 1rem;
}

.nav-item ul li:hover {
    color: rgb(75, 72, 72);
    cursor: pointer;
}
</style>
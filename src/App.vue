<script setup>
import Nav from './components/Nav.vue';
import Footer from './components/Footer.vue';
import Main from './components/Main.vue';
</script>

<template>
  <div class="nav-footer-wrapper">
    <Nav />
    <Main />
    <Footer />
  </div>
</template>

<style scoped>
.nav-footer-wrapper {
  display: flex;
  flex-direction: column;
}
</style>

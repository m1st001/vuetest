<script setup lang="ts">
   import { RouterLink } from 'vue-router';
   import Header from './components/global/Header.vue';
   import Card from './components/eventCards/Card.vue';
   import Footer from './components/global/Footer.vue';
</script>

<template>
    <Header></Header>
    <div class="container-md">
        <div class="container border border-secondary rounded bg-body-tertiary vh-100 mt-5">
            <div class="list-group">
                <Card></Card>
                <Card></Card>
            </div>
        </div>
    </div>
    <Footer></Footer>
</template>

<style scoped>
</style>
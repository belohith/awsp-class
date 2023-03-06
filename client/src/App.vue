<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import Flyout from './components/Flyout.vue';
import Cart from './components/Cart.vue';
//ctrl shift p, then format document 

</script>

<template>
    <div>
    <NavBar />


    <div class="container">
        <RouterView />
    </div>
    <Flyout>
        <Cart />
    </Flyout>
    </div>
</template>

<style scoped></style>
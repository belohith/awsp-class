<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Cart from './components/Cart.vue';
import Flyout from './components/Flyout.vue';
import NavBar from './components/NavBar.vue';


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

<style scoped>

</style>
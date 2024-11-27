<script setup>
import { ref } from 'vue';
import Search from './components/Search.vue';
import Products from './components/Products.vue';
</script>

<template>
    <div class="container-md">
        <div class="row">
            <div class="col-lg-12 text-center">
            <h1 class="mt-4">Магазин</h1>
            <Search />
            <Products />
        </div>
    </div>
</div>
</template>

<style>

</style>

<script setup>
import { onMounted } from "vue"
import { Head } from '@inertiajs/vue3'
import { greeting } from "../custom.js";

onMounted(() => {
    greeting('John Doe');
});
</script>

<template>
    <Head>
        <title>Home</title>
    </Head>

    <header>Home</header>

    <section>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facere, illum.</section>

    <footer>ääääöööö</footer>
</template>

<style scoped>
@import "../../css/custom.css";
</style>

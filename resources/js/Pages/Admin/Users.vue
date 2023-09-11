<script setup>
import { onMounted } from "vue"
import { Head } from '@inertiajs/vue3'
import '../../../css/admin.css';
import { greeting } from "../../admin.js";

onMounted(() => {
    greeting('John Doe');
});
</script>

<template>
    <Head>
        <title>Users</title>
    </Head>

    <header>Users</header>
    
    <section>
        <ul>
            <li>User 1</li>
            <li>User 2</li>
            <li>User 3</li>
            <li>User 4</li>
            <li>User 5</li>
            <li>User 6</li>
        </ul>
    </section>

    <footer>ääääöööö</footer>
</template>

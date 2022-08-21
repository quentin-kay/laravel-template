<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import route from 'ziggy-js';

defineProps({
    laravelVersion: String,
    phpVersion: String,
})
</script>

<template>
    <Head><title>Welcome</title></Head>

    <h1>Welcome!</h1>
    <br />
    <p>Laravel Version: {{ laravelVersion }}</p>
    <p>PHP Version: {{ phpVersion }}</p>
    <Link :href="route('test')">Test</Link>
</template>
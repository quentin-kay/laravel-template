<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import route from 'ziggy-js';
</script>

<template>
    <Head><title>Test</title></Head>

    <h1>TEST!</h1>
    <br />
    <Link :href="route('home')">Home</Link>
</template>
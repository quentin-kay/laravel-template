<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
</script>

<template>
    <Head title="Test" />

    <h1>TEST!</h1>
    <br />
    <Link :href="route('home')">Home</Link>
</template>
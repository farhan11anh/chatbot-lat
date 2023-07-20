<template>
    <div>
        <Navbar />
        <h2>About Page </h2>

        <div class="flex gap-7">
            <Card-comp />
            <Card-comp />
            <Card-comp />

        </div>
    </div>
</template>

<script setup>
    definePageMeta({
        layout: "default",
    });
</script>

<style>
    
</style>
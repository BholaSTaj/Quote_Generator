<script setup>
    import {ref} from 'vue'
    const heading = ref("Quote Generator")
    heading.value = ("Minimilastics Quote")
</script>

<template>
    <header>
        <h1>{{ heading }}</h1>
    </header>
</template>

<style scoped>
    header h1{
        color: #CCD6D9;
        margin-bottom: 20px;
    }
</style>
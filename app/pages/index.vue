<template>
    <h1>Hello World....</h1>
    <NuxtLink to="/about">About</NuxtLink>  
</template>

<script lang="ts" setup>
    useHead({
        title: 'My awesome Website',
    });
</script>
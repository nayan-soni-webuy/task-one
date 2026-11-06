<template>
    <h1 class="text-4xl font-black">Hello World....</h1>
    <NuxtLink to="/about">About</NuxtLink>  
</template>

<script lang="ts" setup>
    useHead({
        title: 'My awesome Website',
    });
</script>
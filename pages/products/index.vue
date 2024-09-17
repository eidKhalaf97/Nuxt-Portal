<template>
    <div>
        <h1>Products</h1>
        <div v-for="p in products">
            <NuxtLink :to="`/products/${p.id}`">{{ p.title }}</NuxtLink>
        </div>
    </div>
</template>

<script setup>
    definePageMeta({
        layout: 'products'
    })

    const { data: products } = await useFetch('https://fakestoreapi.com/products')
</script>

<style scoped>

</style>
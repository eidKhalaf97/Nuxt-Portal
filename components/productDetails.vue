<template>
    <div>
        <p>{{ product.title }}</p>
        <p>{{ product.description }}</p>
    </div>
</template>

<script setup>
    defineProps(['product'])
</script>

<style scoped>

</style>
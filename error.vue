<template>
    <div>
        OOPS: {{ error.message }}
    </div>
</template>

<script setup>
    defineProps(['error'])
</script>

<style scoped>

</style>
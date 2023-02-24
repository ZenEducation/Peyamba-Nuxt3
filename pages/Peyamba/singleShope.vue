<template>
    <div>
        <breadcrumb/>
        <products/>
    </div>
</template>

<script setup>

import breadcrumb from '@/components/Peyamba/singleShope/breadcrumb.vue'
import products from '@/components/Peyamba/singleShope/products.vue'
definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
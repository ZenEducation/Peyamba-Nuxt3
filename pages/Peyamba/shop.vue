<template>
    <div>
        
        <breadcrumb/>
        <product/>
        
    </div>
</template>

<script setup>
    
    import breadcrumb from '@/components/Peyamba/Shop/breadcrumb.vue'
    import product from '@/components/Peyamba/Shop/product.vue'
    definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
<template>
    <div>
        <breadcrumb/>
        <mainComp/>
    </div>
</template>

<script setup>

import breadcrumb from '@/components/peyamba/503error/breadcrumb.vue'
import mainComp from '@/components/peyamba/503error/mainComp.vue'
definePageMeta({
        layout: 'frontend-layout'
    })

</script>

<style lang="scss" scoped>

</style>
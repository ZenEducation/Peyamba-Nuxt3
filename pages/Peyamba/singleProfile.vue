<template>
    <div>
        <breadcrumb/>
        <profile/>
    </div>
</template>

<script setup>

import breadcrumb from '@/components/Peyamba/singleProfile/breadcrumb.vue'
import profile from '@/components/Peyamba/singleProfile/profile.vue'
definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
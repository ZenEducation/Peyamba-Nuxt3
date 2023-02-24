<template>
    <div>
        <breadcrumb/>
        <contact/>
    </div>
</template>

<script setup>

import breadcrumb from '@/components/Peyamba/contact/breadcrumb.vue'
import contact from '@/components/Peyamba/contact/contactSection.vue'
definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
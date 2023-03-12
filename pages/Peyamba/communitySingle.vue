<template>
    <div>
        <breadcrumb/>
        <communication/>
        <profile/>
    </div>
</template>

<script setup>
import breadcrumb from '@/components/Peyamba/communitySingle/breadcrumb.vue'
import communication from '@/components/Peyamba/communitySingle/commuSection.vue'
import profile from '@/components/Peyamba/communitySingle/profileSection.vue'
definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
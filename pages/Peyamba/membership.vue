<template>
    <div>
    
        <breadcrumb/>
        <member/>
        <faq/>
        
    </div>
</template>

<script setup>
    
    import breadcrumb from '@/components/Peyamba/Membership/breadcrumb.vue'
    import member from '@/components/Peyamba/Membership/memberSection.vue'
    import faq from '@/components/Peyamba/Membership/faq.vue'
    definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style scoped>

</style>
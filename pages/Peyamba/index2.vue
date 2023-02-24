<template>
    <div>
    
        <banner/>
        <steps/>
        <flirting/>
        <member/>
        <features/>
        <joinnow/>
        <community/>
        <statstics/>
        <success/>
        <update/>
        
    </div>
</template>

<script setup>

import banner from '@/components/Peyamba/Index2/banner.vue'
import steps from '@/components/Peyamba/Index2/steps.vue'
import flirting from '@/components/Peyamba/Index2/flirting.vue'
import member from '@/components/Peyamba/Index2/memberSlider.vue'
import features from '@/components/Peyamba/Index/features.vue'
import joinnow from '@/components/Peyamba/Index/joinNow.vue'
import community from '@/components/Peyamba/Index2/community.vue'
import statstics from '@/components/Peyamba/Index2/statistics.vue'
import success from '@/components/Peyamba/Index2/success.vue'
import update from '@/components/Peyamba/Index2/updateProfile.vue'

definePageMeta({
        layout: 'frontend-layout'
    })

</script>

<style scoped>

</style>
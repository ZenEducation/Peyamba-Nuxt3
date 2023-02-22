<template>
    <div>
        
        <banner/>
        <feature/>
        <flirting/>
        <HWT/>
        <statistics/>
        <joinnow/>
        <features/>
        <latest/>
        <success/>
        
    </div>
</template>

<script setup>

import banner from '@/components/Peyamba/Index/banner.vue'
import feature from '@/components/Peyamba/Index/feature.vue'
import flirting from '@/components/Peyamba/Index/flirting.vue'
import HWT from '@/components/Peyamba/Index/howItWorks.vue'
import statistics from '@/components/Peyamba/Index/statistics.vue'
import joinnow from '@/components/Peyamba/Index/joinNow.vue'
import features from '@/components/Peyamba/Index/features.vue'
import latest from '@/components/Peyamba/Index/latestRegistered.vue'
import success from '@/components/Peyamba/Index/successStories.vue'


definePageMeta({
        layout: 'frontend-layout'
    })

</script>

<style lang="scss" scoped>

</style>
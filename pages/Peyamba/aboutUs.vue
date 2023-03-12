<template>
    <div>
        <breadcrumb/>
        <flirting/>
        <wcu/>
        <features/>
        <joinNow/>
        <successStories/>
    </div>
</template>

<script setup>
        import breadcrumb from '~~/components/Peyamba/about/breadcrumb.vue';
        import flirting from "~~/components/Peyamba/about/flirting.vue"
        import wcu from "~~/components/Peyamba/about/wcu.vue"
        import features from '~~/components/Peyamba/Index/features.vue';
        import joinNow from '~~/components/Peyamba/Index/joinNow.vue';
        import successStories from '~~/components/Peyamba/Index/successStories.vue';
    definePageMeta({
        layout: 'frontend-layout'
    })

</script>

<style lang="scss" scoped>

</style>
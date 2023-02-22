<template>
    <div>
        <navbar/>
        <slot/>

        <newslatter/>
    </div>
</template>

<script setup>
    import navbar from '@/components/Peyamba/navbar.vue'
    import newslatter from '@/components/Peyamba/newslatter.vue'
</script>

<style lang="scss" scoped>

</style>
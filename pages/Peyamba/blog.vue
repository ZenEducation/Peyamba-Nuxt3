<template>
    <div>
        <breadcrumb/>
        <content/>
    </div>
</template>

<script setup>
import breadcrumb from '~~/components/Peyamba/blog/breadcrumb.vue';
import content from '~~/components/Peyamba/blog/content.vue';

definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
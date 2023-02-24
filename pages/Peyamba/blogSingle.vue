<template>
    <div>
        <breadcrumb/>
        <content/>
    </div>
</template>

<script setup>
import breadcrumb from '~~/components/Peyamba/blogSingle/breadcrumb.vue';
import content from '~~/components/Peyamba/blogSingle/content.vue';

definePageMeta({
        layout: 'frontend-layout'
    })
</script>

<style lang="scss" scoped>

</style>
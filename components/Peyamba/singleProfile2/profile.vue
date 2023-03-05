<template>
    <div>
        <section class="px-0 py-[120px] block">
            <div class="container mx-auto sm:px-4 w-full px-[15px]">
                <div class="flex flex-wrap  justify-center mr-[-15px] ml-[-15px]">
                    <div class="xl:w-1/3  lg:w-2/5  md:w-3/5 pr-4 pl-4 relative w-full ">
                        <left_profile_area />
                    </div>
                    <div class="xl:w-2/5 pr-4 pl-4 lg:w-1/2 ">
                        <profile_main_content />
                    </div>
                    <div class="xl:w-1/4 pr-4 pl-4 lg:w-2/5  md:w-3/5 ">
                        <profile_aside_area />
                    </div>
                </div>
            </div>
    
    </section>
</div></template>

<script setup>
import left_profile_area from '../singleProfile/left_profile_area.vue';
import profile_main_content from './profile_main_content.vue';
import profile_aside_area from '../singleProfile/profile_aside_area.vue';
</script>

<style lang="scss" scoped></style>
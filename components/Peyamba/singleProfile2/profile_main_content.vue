<template>
    <div>
        <div class="profile-main-content">
            <ul class="bg-white shadow-[0px_5px_30px_0px_rgba(35,57,184,0.2)] block text-center mb-px pt-1.5 pb-2.5 px-2.5 rounded-[10px]">
                <li class="inline-block">
                    <NuxtLink to="/peyamba/singleprofile" class="text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Activity
                    </NuxtLink>
                </li>
                <li class="inline-block">
                    <NuxtLink to="/peyamba/singleprofile2" class="active text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Profile
                    </NuxtLink>
                </li>
                <li class="inline-block">
                    <NuxtLink to="/peyamba/singleprofile3" class="text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Friends
                        <div class="num absolute bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-[10px] leading-[10px] text-white right-[-17px] px-[5px] py-[3px] rounded-[30px] -top-1.5">04</div>
                    </NuxtLink>
                </li>
                <li class="inline-block">
                    <NuxtLink to="/peyamba/profilenotfound" class="text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Groups
                        <div class="num absolute bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-[10px] leading-[10px] text-white right-[-17px] px-[5px] py-[3px] rounded-[30px] -top-1.5">14</div>
                    </NuxtLink>
                </li>
                <li class="inline-block">
                    <NuxtLink to="/peyamba/profilenotfound" class="text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Media
                        <div class="num absolute bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-[10px] leading-[10px] text-white right-[-17px] px-[5px] py-[3px] rounded-[30px] -top-1.5">47</div>
                    </NuxtLink>
                </li>
            </ul>
            <div class="info-box bg-white mt-[30px] pt-[30px] pb-[22px] px-[30px] rounded-[10px]">
                <div class="header border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                    <h4 class="title text-2xl leading-[34px] font-semibold pb-2.5">
                        Base
                    </h4>
                </div>
                <div class="content">
                    <ul class="infolist">
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Name
                            </span>
                            <span class="text-base leading-[26px]">
                                Albert Don
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Birthday
                            </span>
                            <span class="text-base leading-[26px]">
                                1998-01-19
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                I am a
                            </span>
                            <span class="text-base leading-[26px]">
                                Man
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Looking for a
                            </span>
                            <span class="text-base leading-[26px]">
                                Woman
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Marital status
                            </span>
                            <span class="text-base leading-[26px]">
                                single
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Country
                            </span>
                            <span class="text-base leading-[26px]">
                                France
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b-0 border-dashed">
                            <span class="text-base leading-[26px]">
                                City
                            </span>
                            <span class="text-base leading-[26px]">
                                Paris
                            </span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="info-box bg-white mt-[30px] pt-[30px] pb-[22px] px-[30px] rounded-[10px]">
                <div class="header border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                    <h4 class="title text-2xl leading-[34px] font-semibold pb-2.5">
                        Myself Summary
                    </h4>
                </div>
                <div class="content">
                    <p class="text text-base leading-[26px] mb-0 pt-5 pb-[3px] px-0">
                        I don`t like talk too much to be honest and especially about myself. I am man of
                        actions, I do a lot of sports, I adore to travel and to see the world.
                    </p>
                </div>
            </div>
            <div class="info-box bg-white mt-[30px] pt-[30px] pb-[22px] px-[30px] rounded-[10px]">
                <div class="header border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                    <h4 class="title text-2xl leading-[34px] font-semibold pb-2.5">
                        Lifestyle
                    </h4>
                </div>
                <div class="content">
                    <ul class="infolist">
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Interests
                            </span>
                            <span class="text-base leading-[26px]">
                                Billiards
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Looking for
                            </span>
                            <span class="text-base leading-[26px]">
                                Just friends
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Smoking
                            </span>
                            <span class="text-base leading-[26px]">
                                Never
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b-0 border-dashed">
                            <span class="text-base leading-[26px]">
                                Language
                            </span>
                            <span class="text-base leading-[26px]">
                                English
                            </span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="info-box bg-white mt-[30px] pt-[30px] pb-[22px] px-[30px] rounded-[10px]">
                <div class="header border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                    <h4 class="title text-2xl leading-[34px] font-semibold pb-2.5">
                        Physical
                    </h4>
                </div>
                <div class="content">
                    <ul class="infolist">
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Height
                            </span>
                            <span class="text-base leading-[26px]">
                                5’10
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Weight
                            </span>
                            <span class="text-base leading-[26px]">
                                71
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Hair Color
                            </span>
                            <span class="text-base leading-[26px]">
                                Black
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span class="text-base leading-[26px]">
                                Eye Color
                            </span>
                            <span class="text-base leading-[26px]">
                                Brown
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b-0 border-dashed">
                            <span class="text-base leading-[26px]">
                                Body Type
                            </span>
                            <span class="text-base leading-[26px]">
                                Tall
                            </span>
                        </li>
                        <li class="flex justify-between border-b-[rgba(0,0,0,0.1)] border-b border-dashed">
                            <span  class="text-base leading-[26px]">
                                Ethnicity
                            </span>
                            <span  class="text-base leading-[26px]">
                                Middle Eastern
                            </span>
                        </li>
                    </ul>
                </div>
            </div>

        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>
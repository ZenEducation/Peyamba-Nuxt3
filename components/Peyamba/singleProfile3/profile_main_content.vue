<template>
    <div>
        <div class="">
            <ul class="bg-white shadow-[0px_5px_30px_0px_rgba(35,57,184,0.2)] block text-center mb-px pt-1.5 pb-2.5 px-2.5 rounded-[10px]">
                <li class="inline-block">
                    <NuxtLink to="/peyamba/singleprofile" class="text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Activity
                    </NuxtLink>
                </li>
                <li class="inline-block">
                    <NuxtLink to="/peyamba/singleprofile2" class=" text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
                        Profile
                    </NuxtLink>
                </li>
                <li class="inline-block">
                    <NuxtLink to="/peyamba/singleprofile3" class="active text-[#333333] text-base leading-[26px] font-bold relative transition-all duration-[ease] delay-[0.3s] mx-3 my-0 active:text-[#ac216c] hover:text-[#ac216c]">
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
            <div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend1.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="text-xl leading-[30px] font-bold text-[#333333]">
                            Erma Porter
                            <div class="inline-block">
                                <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend2.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="text-xl leading-[30px] font-bold text-[#333333]">
                            Vicki Alvarez
                            <div class="inline-block">
                                <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend3.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="name text-xl leading-[30px] font-bold text-[#333333]">
                            Opal Farmer
                            <div class="inline-block">
                                <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend4.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="name text-xl leading-[30px] font-bold text-[#333333]">
                            May Hart
                            <div class="inline-block">
                                <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend5.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="name text-xl leading-[30px] font-bold text-[#333333]">
                            Julia Salazar
                            <div class="inline-block">
                                <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend6.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="name text-xl leading-[30px] font-bold text-[#333333]">
                            Joy Bailey
                            <div class="inline-block">
                                <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
                <div class="flex border mt-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)]">
                    <img src="@/assets/frontend/images/profile/friend7.png" class="max-w-[80px] mr-5" alt="">
                    <div class="flex-[1] self-center relative pr-[150px]">
                        <NuxtLink to="/peyamba/communitysingle" class="name text-xl leading-[30px] font-bold text-[#333333]">
                            Julie Dunn
                            <div class="inline-block">
                                <i class="fas fa-check-circle  bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                            </div>
                        </NuxtLink>
                        <p class="text-base leading-[26px] mb-0">
                            a month ago
                        </p>
                        <NuxtLink to="/peyamba/communitysingle" class="absolute -traslate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                            Connected
                        </NuxtLink>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>
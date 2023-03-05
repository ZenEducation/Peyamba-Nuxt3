<template>
    <div>
        <div class="left-profile-area">
            <div
                class=" bg-white shadow-[0px_10px_5px_0px_rgb(119_123_146_/_2%)] transition-all duration-[ease] delay-[0.3s] rounded-[10px]">
                <div
                    class="h-40 bg-[url('../images/profile/profile-box-bg.png')] bg-no-repeat bg-[bottom_center] bg-contain">
                </div>
                <div class="relative text-center pt-[90px] pb-[30px] px-[30px]">
                    <div
                        class=" bg-white w-[120px] h-[120px] absolute -translate-x-2/4 top-[-60px] z-[9] rounded-[50%] left-2/4 before:absolute before:content-[''] before:w-[140px] before:h-[140px] before:bg-[rgba(255,255,255,0.2)] before:z-[-1] before:rounded-[50%] before:-left-2.5 before:-top-2.5 before:box-border after:box-border after:absolute after:content-[''] after:w-40 after:h-40 after:bg-[rgba(255,255,255,0.2)] after:z-[-1] after:rounded-[50%] after:-left-5 after:-top-5">
                        <img src="@/assets/frontend/images/profile/profile-user.png"
                            class="align-middle rounded-[50%] border-none" alt="">
                        <div
                            class="absolute w-5 h-5 bg-[#1ce36f] rounded-[50%] border-[3px] border-solid border-white right-[9px] bottom-[9px]">
                        </div>
                    </div>
                    <h5 class="text-[28px] leading-[38px] text-[#333333] -mt-2 mb-0 mx-0 font-['Fira_Sans',sans]">
                        Albert Don
                    </h5>
                    <ul>
                        <li class="inline-block mr-[30px] px-0 py-[5px] list-none">
                            <span>21 Years Old</span>
                        </li>
                        <li
                            class="inline-block mr-0 px-0 py-[5px] relative before:absolute before:content-['|'] left-[-18px] top-0.5 box-border">
                            <span> <i
                                    class="fas fa-map-marker-alt bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] inline-block not-italic leading-none font-black mx-[7px] font-['Font_Awesome_5_Free']"></i>Paris,France</span>
                        </li>
                    </ul>
                    <div class="flex justify-between mt-5">
                        <div class="font-semibold">
                            <div class=" w-10 h-10 bg-[#f7e9f8] text-center leading-10 inline-block rounded-[50%]">
                                <i
                                    class="far fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] font-normal font-['Font_Awesome_5_Free'] inline-block not-italic leading-none text-clip fill-transparent"></i>
                            </div> 257
                        </div>
                        <div>
                            <a href="#"
                                class="inline-block font-[normal] bg-[linear-gradient(-51deg,rgb(246,100,188)_0%,rgb(251,123,188)_35%,rgb(255,146,187)_100%)] shadow-[0px_5px_20px_0px_rgb(139_122_132_/_50%)] text-white cursor-pointer w-auto h-auto px-[15px] py-[5px] rounded-[50px] border-0">
                                <i class="fab fa-cloudversify inline-block not-italic leading-none"></i> Get Premium
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div
                class="bg-white shadow-[0px_10px_5px_0px_rgb(119_123_146_/_2%)] transition-all duration-[ease] delay-[0.3s] mt-[30px] p-5 rounded-[10px]">
                <ul class="flex flex-wrap w-full">
                    <li class="flex-[33.33%] w-[33.33%] text-center px-0 py-[5px] list-none">
                        <a href="#" data-toggle="modal" data-target="#usermessage"
                            class="w-[60px] h-[60px] bg-[#f8e9f7] leading-[60px] relative inline-block transition-all duration-[ease] delay-[0.3s] no-underline rounded-[50%]">
                            <i
                                class="far fa-envelope bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-xl inline-block not-italic leading-none font-normal font-['Font_Awesome_5_Free']"></i>
                            <div
                                class="absolute w-5 h-5 leading-5 bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-[10px] text-white z-[2] rounded-[50%] right-[15%] top-[15%]">
                                04</div>
                        </a>
                    </li>
                    <li class="flex-[33.33%] w-[33.33%] text-center px-0 py-[5px] list-none">
                        <a href="#" data-toggle="modal" data-target="#usernotification"
                            class="w-[60px] h-[60px] bg-[#f8e9f7] leading-[60px] relative inline-block transition-all duration-[ease] delay-[0.3s] no-underline rounded-[50%]">
                            <i
                                class="far fa-bell bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-xl inline-block not-italic leading-none font-normal font-['Font_Awesome_5_Free']"></i>
                            <div
                                class="absolute w-5 h-5 leading-5 bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-[10px] text-white z-[2] rounded-[50%] right-[15%] top-[15%]">
                                04</div>
                        </a>
                    </li>
                    <li class="flex-[33.33%] w-[33.33%] text-center px-0 py-[5px] list-none">
                        <a href="#"
                            class="w-[60px] h-[60px] bg-[#f8e9f7] leading-[60px] relative inline-block transition-all duration-[ease] delay-[0.3s] no-underline rounded-[50%]">
                            <i
                                class="fas fa-cogs bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-xl inline-block not-italic leading-none font-normal font-['Font_Awesome_5_Free']"></i>
                        </a>
                    </li>
                </ul>
            </div>
            <div
                class=" bg-white shadow-[0px_10px_5px_0px_rgb(119_123_146_/_2%)] transition-all duration-[ease] delay-[0.3s] mt-[30px] pt-[35px] pb-2.5 px-5 rounded-[10px]">
                <h4
                    class="p-u-p-header text-2xl font-semibold block leading-[1.3] text-[#333333] mb-[25px] m-0 px-2.5 py-0 font-['Fira_Sans',_sans-serif]">
                    <i
                        class="fas fa-camera bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] inline-block not-italic leading-none font-black mr-[7px] font-['Font_Awesome_5_Free'] before:content-['\f030']"></i>
                    21 Upload Photos
                </h4>
                <div class="p-u-p-list flex flex-wrap">
                    <div class="my-col w-[33.33%] flex-[33.33%] px-2.5">
                        <div class="img relative overflow-hidden mb-5 rounded-[15px]">
                            <div class="group">
                                <img src="@/assets/frontend/images/profile/up1.jpg" class="w-full" alt="">
                                <div
                                    class="absolute overlay w-full h-full bg-[rgb(85,51,202)] opacity-0 transition-all duration-[ease] delay-[0.3s] scale-[0.3] left-0 top-0 group-hover:opacity-80 group-hover:scale-100">
                                    <a href="@/assets/frontend/images/profile/up1.jpg"
                                        class="img-popup text-white absolute -translate-x-2/4 -translate-y-2/4 cursor-pointer left-2/4 top-2/4"><i
                                            class="fas fa-plus"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="my-col w-[33.33%] flex-[33.33%] px-2.5">
                        <div class="img relative overflow-hidden mb-5 rounded-[15px]">
                            <div class="group">
                                <img src="@/assets/frontend/images/profile/up2.jpg" class="w-full" alt="">
                                <div
                                    class="absolute overlay w-full h-full bg-[rgb(85,51,202)] opacity-0 transition-all duration-[ease] delay-[0.3s] scale-[0.3] left-0 top-0 group-hover:opacity-80 group-hover:scale-100">
                                    <a href="@/assets/frontend/images/profile/up2.jpg"
                                        class="img-popup text-white absolute -translate-x-2/4 -translate-y-2/4 cursor-pointer left-2/4 top-2/4"><i
                                            class="fas fa-plus"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="my-col w-[33.33%] flex-[33.33%] px-2.5">
                        <div class="img relative overflow-hidden mb-5 rounded-[15px]">
                            <div class="group">
                                <img src="@/assets/frontend/images/profile/up3.jpg" class="w-full" alt="">
                                <div
                                    class="absolute overlay w-full h-full bg-[rgb(85,51,202)] opacity-0 transition-all duration-[ease] delay-[0.3s] scale-[0.3] left-0 top-0 group-hover:opacity-80 group-hover:scale-100">
                                    <a href="@/assets/frontend/images/profile/up3.jpg"
                                        class="img-popup text-white absolute -translate-x-2/4 -translate-y-2/4 cursor-pointer left-2/4 top-2/4"><i
                                            class="fas fa-plus"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="my-col w-[33.33%] flex-[33.33%] px-2.5">
                        <div class="img relative overflow-hidden mb-5 rounded-[15px]">
                            <div class="group">
                                <img src="@/assets/frontend/images/profile/up4.jpg" class="w-full" alt="">
                                <div
                                    class="absolute overlay w-full h-full bg-[rgb(85,51,202)] opacity-0 transition-all duration-[ease] delay-[0.3s] scale-[0.3] left-0 top-0 group-hover:opacity-80 group-hover:scale-100">
                                    <a href="@/assets/frontend/images/profile/up4.jpg"
                                        class="img-popup text-white absolute -translate-x-2/4 -translate-y-2/4 cursor-pointer left-2/4 top-2/4"><i
                                            class="fas fa-plus"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="my-col w-[33.33%] flex-[33.33%] px-2.5">
                        <div class="img relative overflow-hidden mb-5 rounded-[15px]">
                            <div class="group">
                            <img src="@/assets/frontend/images/profile/up5.jpg" class="w-full" alt="">
                            <div
                                class="absolute overlay w-full h-full bg-[rgb(85,51,202)] opacity-0 transition-all duration-[ease] delay-[0.3s] scale-[0.3] left-0 top-0 group-hover:opacity-80 group-hover:scale-100">
                                <a href="@/assets/frontend/images/profile/up5.jpg"
                                    class="img-popup text-white absolute -translate-x-2/4 -translate-y-2/4 cursor-pointer left-2/4 top-2/4"><i
                                        class="fas fa-plus"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="my-col w-[33.33%] flex-[33.33%] px-2.5">
                    <div class="img relative overflow-hidden mb-5 rounded-[15px]">
                        <div class="group">
                            <img src="@/assets/frontend/images/profile/up6.jpg" class="w-full" alt="">
                            <div
                                class="absolute w-full h-full bg-[rgb(85,51,202)] opacity-0 transition-all duration-[ease] delay-[0.3s] scale-[0.3] left-0 top-0 group-hover:opacity-80 group-hover:scale-100">
                                <a href="@/assets/frontend/images/profile/up6.jpg"
                                    class="img-popup text-white absolute -translate-x-2/4 -translate-y-2/4 cursor-pointer left-2/4 top-2/4 "><i
                                        class="fas fa-plus"></i></a>
                            </div>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div></template>

<script setup>

</script>

<style lang="scss" scoped></style>
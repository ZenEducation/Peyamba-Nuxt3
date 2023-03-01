<template>
    <div>
        <section class="banner-section home2 bg-[url('../images/banner/hero-banner2.jpg')] bg-no-repeat bg-bottom bg-cover relative overflow-hidden pt-[189px] pb-[220px] px-0">
        <img class="img3 absolute animate-[leftRight_4s_linear_infinite] right-[5%]" src="@/assets/frontend/images/banner/aimg3.png" alt="">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap ">
                <div class="xl:w-1/3 lg:w-2/5 pr-4 pl-4">
                    <h1 class="text-6xl leading-[70px] font-bold uppercase text-white text-center mb-[15px]">
                        Find Love Your Life
                    </h1>
                    <div class="bg-white shadow-[0px_3px_10px_0px_rgba(0,0,0,0.1)] pt-[23px] pb-[60px] px-0 rounded-[30px]">
                        <div class="flex pt-[22px] pb-[15px] px-5 border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                            <p class="text-lg leading-7 font-bold relative mr-5 top-[7px]">
                                I am a :
                            </p>
                            <div class="flex items-center">
                                <div class="mr-3">
                                    
                                    <input type="radio" name="gender" id="males" checked class="w-5 h-5 border rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="males" class=" ml-2">Man</label>
                                </div>
                                <div>
                                   
                                    <input type="radio" name="gender" id="females" class="w-5 h-5 border  rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="females" class=" ml-2">Woman</label>
                                </div>
                            </div>
                        </div>
                        <div class="flex pt-[22px] pb-[15px] border-b-[rgba(0,0,0,0.1)] border-b border-solid px-5 py-[17px]">
                            <p class="title text-lg leading-7 font-bold relative mr-5 top-[7px]">
                                Seeking a :
                            </p>
                            <div class="flex items-center">
                                <div class="mr-4">
                                    
                                    <input type="radio" name="seeking" id="males" checked class="w-5 h-5 border rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="males" class=" ml-2">Man</label>
                                </div>
                                
                                <div>
                                    <input type="radio" name="seeking" id="females" class="w-5 h-5 border  rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="females" class=" ml-2">Woman</label>
                                </div>
                            </div>
                        </div>
                        <div class="flex  border-b-[rgba(0,0,0,0.1)] border-b border-solid pt-[21px] pb-5 px-5">
                            <p class="text-lg leading-7 font-bold relative mr-5 top-[7px]">
                                Ages :
                            </p>
                            <div class="flex items-center">
                                <div class="mr-3">
                                    <select class="w-[90px] bg-transparent leading-[26px] border h-auto pl-[15px] pr-[30px] py-0 rounded-[50px] border-solid border-[rgba(0,0,0,0.1)]">
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">18</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">20</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">24</option>
                                    </select>
                                </div>
                                <div>
                                    -
                                </div>
                                <div class="ml-3">
                                    <select class="w-[90px] bg-transparent leading-[26px] border h-auto pl-[15px] pr-[30px] py-0 rounded-[50px] border-solid border-[rgba(0,0,0,0.1)]">
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">30</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">35</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">40</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                        <div class="flex  border-b-[rgba(0,0,0,0.1)] border-solid pt-[29px] pb-7 px-5 border-b-0">
                            <p class="top-1  text-lg leading-7 font-bold relative mr-5 ">
                                Country :
                            </p>
                            <div class="items-center">
                                <div class="s-input mr-3">
                                    <select class="select-bar w-[190px] px-2.5 bg-transparent leading-[26px] border h-auto pl-[15px] pr-[30px] py-0 rounded-[50px] border-solid border-[rgba(0,0,0,0.1)]">
                                        <option class="text-[#222] leading-5 px-2.5 py-0;">Select Country</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">India</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">Japan</option>
                                        <option class="text-[#222] leading-5 px-2.5 py-0;" value="">England</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                        <div class="text-center">
                            <button class="bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] font-semibold text-white inline-block cursor-pointer w-auto h-auto px-[35px] py-[11px] rounded-[50px] border-0 hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)]">Join Now!</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>
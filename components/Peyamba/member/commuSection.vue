<template>
    <div>
        <section>
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap ">
                <div class="lg:w-full pr-4 pl-4">
                    <div class="flex justify-between mb-[30px] px-0 py-5 border-y-[rgba(0,0,0,0.1)] border-t border-solid border-b">
                        <div>
                            <NuxtLink to="#" data-toggle="modal" data-target="#exampleModalCenter" class="bg-[rgb(238,243,251)] shadow-[0px_5px_10px_0px_rgba(143,175,202,0.5)] text-[#333] px-[30px] py-1.5 rounded-[50px] no-underline">
                                <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] mr-1"></i> Filter your search
                            </NuxtLink>
                        </div>
                        <div>
                            <span class="text-base leading-[26px] relative mr-[7px] -top-2">
                                Order By : 
                            </span>
                            <div class="inline-block">
                                <select class="relative min-w-[105px] inline-block bg-[rgb(238,243,251)] shadow-[0px_5px_10px_0px_rgba(143,175,202,0.5)] cursor-pointer text-sm h-[35px] leading-[35px] pl-5 pr-[30px] p-0 rounded-[50px] top-1">
                                    <option value="" class=" selection:text-xs selection:uppercase selection:leading-3 block text-xs uppercase min-h-[30px] leading-[30px] px-[5px] py-0">Latest Active</option>
                                    <option value="" class=" selection:text-xs selection:uppercase selection:leading-3 block text-xs uppercase min-h-[30px] leading-[30px] px-[5px] py-0">NEW</option>
                                    <option value="" class=" selection:text-xs selection:uppercase selection:leading-3 block text-xs uppercase min-h-[30px] leading-[30px] px-[5px] py-0">OLD</option>
                                    <option value="" class=" selection:text-xs selection:uppercase selection:leading-3 block text-xs uppercase min-h-[30px] leading-[30px] px-[5px] py-0">POPULAR</option>
                                </select>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-wrap ">
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend1.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Erma Porter
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend2.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Brad Barber 
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend3.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Vicki Alvarez 
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend4.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Amber Perry
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend5.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Kelly Fox 
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend6.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Opal Farmer 
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend7.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                May Hart 
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend8.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Ana Byrd
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend9.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Arthur Bass
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="flex border transition-all duration-[ease] delay-[0.3s] mt-0 mb-[30px] p-5 rounded-[15px] border-solid border-[rgba(0,0,0,0.1)] hover:border-[#5650ce]">
                        <img src="@/assets/frontend/images/profile/friend10.png" class="max-w-[80px] mr-5" alt="">
                        <div class="flex-[1] self-center relative pr-[150px]">
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline name text-xl leading-[30px] font-bold text-[#333333]">
                                Stewart Bailey 
                                <span class="inline-block">
                                    <i class="fas fa-check-circle bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-base ml-1"></i>
                                </span>
                            </NuxtLink>
                            <p class="text-base leading-[26px] mb-0">
                                a month ago
                            </p>
                            <NuxtLink to="/peyamba/singleprofile" class=" no-underline absolute -translate-y-2/4 z-[1] flex-[16px] text-[#333] border px-5 py-1.5 rounded-[50px] border-solid border-[rgba(0,0,0,0.15)] right-0 top-2/4 hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:text-white">
                                Connected
                            </NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-wrap">
              <div class="lg:w-full pr-4 pl-4">
                <div class="text-lg mr-[-15px] ml-[-15px] my-0 text-center">
                  <NuxtLink
                    to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)]"
                    ><i class="fas fa-angle-double-left"></i><span></span
                  ></NuxtLink>
                  <NuxtLink
                    to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline"
                    >1</NuxtLink
                  >
                  <NuxtLink
                    to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline"
                    >2</NuxtLink
                  >
                  <NuxtLink
                    to="#"
                    class="shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-white no-underline"
                    >3</NuxtLink
                  >
                  <NuxtLink
                    to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline"
                    >4</NuxtLink
                  >
                  <NuxtLink
                    to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline"
                    >5</NuxtLink
                  >
                  <NuxtLink
                    to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline"
                    ><i class="fas fa-angle-double-right"></i
                  ></NuxtLink>
                </div>
              </div>
            </div>
        </div>
    </section>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>
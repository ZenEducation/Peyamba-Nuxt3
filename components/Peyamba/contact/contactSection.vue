<template>
    <div>
        <section class="relative pt-[118px] pb-[120px] px-0">
        <img class="absolute left-0 top-[35%]" src="@/assets/frontend/images/contact/img-left.png" alt="">
        <img class="absolute right-0 top-[30%]" src="@/assets/frontend/images/contact/img-right.png" alt="">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap  justify-center">
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div>
                        <div class=" text-center mb-[30px]">
                            <h6 class="sub-title text-[#5650ce] block text-2xl leading-[34px] font-semibold mb-6">
                                Contact Us
                            </h6>
                            <h2 class="text-[50px] leading-[60px] font-bold block text-[#292929] mb-[11px]">
                                Get in Touch
                            </h2>
                            <p class="inline-block text-[#333333]">
                                We'd love to hear from you! Let us know how we can help.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-wrap ">
                <div class="lg:w-3/5 pr-4 pl-4">
                    <div>
                        <div class="relative mb-[30px]">
                            <i style="display: grid; place-content: center;" class="far fa-user absolute -translate-y-2/4 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] w-[30px] h-[30px] text-center leading-[30px] text-white text-sm rounded-[50%] top-2/4"></i>
                            <input type="text" placeholder="Full Name" class="h-[50px] pl-[49px] pr-5 py-0 rounded-none border-t-0 border-b-[rgba(0,0,0,0.1)] border-x-0 border-b border-solid placeholder:text-[#8790ad] placeholder:text-base">
                        </div>
                        <div class="relative mb-[30px]">
                            <i style="display: grid; place-content: center;" class="far fa-envelope absolute -translate-y-2/4 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] w-[30px] h-[30px] text-center leading-[30px] text-white text-sm rounded-[50%] top-2/4"></i>
                            <input type="text" placeholder="Enter Your Email ID" class="h-[50px] pl-[49px] pr-5 py-0 rounded-none border-t-0 border-b-[rgba(0,0,0,0.1)] border-x-0 border-b border-solid placeholder:text-[#8790ad] placeholder:text-base">
                        </div>
                        <div class="relative mb-[30px]">
                            <i style="display: grid; place-content: center;" class="far fa-comments absolute -translate-y-2/4 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] w-[30px] h-[30px] text-center leading-[30px] text-white text-sm rounded-[50%] top-2/4"></i>
                            <textarea placeholder="Type Your Text" class="h-[260px] bg-[none] mt-1.5 pl-[49px] pr-5 p-0 rounded-none border-t-0 border-b-[rgba(0,0,0,0.1)] border-x-0 border-b border-solid placeholder:text-[#8790ad] placeholder:text-base"></textarea>
                        </div>
                        <NuxtLink to="#" class=" no-underline uppercase bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] font-semibold text-white inline-block cursor-pointer w-auto h-auto px-[35px] py-[11px] rounded-[50px] border-0 hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)]">Submit</NuxtLink>
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
<template>
    <div>
        <section class="relative h-screen w-full">
            <div>
                <div class="container mx-auto sm:px-4">
                    <div class="flex flex-wrap ">
                        <div class="lg:w-2/5 pr-4 pl-4">
                            <NuxtLink to="/peyamba" class="backto-home text-white px-0 py-[15px] hover:underline"><i class="fas fa-chevron-left  mr-[5px]"></i> Back to peyamba</NuxtLink>
                        </div>
                        <div class="lg:w-3/5 pr-4 pl-4 ">
                            <div class="block text-left px-0 py-[15px]">
                                <img src="@/assets/frontend/images/logo2.png" class="inline-block" alt="logo">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container mx-auto sm:px-4">
                <div class="flex flex-wrap  justify-end">
                    <div class="bg-[url(@/assets/frontend/images/log.jpg)] bg-no-repeat bg-center bg-cover h-screen w-[43%] absolute z-[-1] left-0 top-0">
                    </div>
                    <div class="lg:w-3/5 pr-4 pl-4">
                        <div class="h-[calc(100vh_-_72px)] overflow-y-auto pr-10 pt-[30px] pb-10">
                            <div class="text-center mb-[30px] pt-20">
                                <h2 class="text-[28px] leading-[38px] capitalize">
                                    Welcome to PEYAMBA
                                </h2>
                            </div>
                            <div>
                                <form action="#">
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Your Address</label>
                                        <input type="email" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder:text-[#3b368c]" placeholder="Enter Your Email">
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Password</label>
                                        <input type="text" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder:text-[#3b368c]" placeholder="Enter Your Password">
                                    </div>
                                    <p class="text-base">
                                        Forgot your password? <a href="#" class="text-[#3b368c] font-semibold hover:underline">recover password</a>
                                    </p>
                                    <div class="block text-center">
                                        <button type="submit" class="bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] font-semibold text-white inline-block cursor-pointer w-auto h-auto px-[35px] py-[11px] rounded-[50px] border-0 hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)]">Sign IN</button>
                                    </div>
                                    <div class="text-base font-bold text-[#3b368c] block text-center relative w-full mt-10 mb-4 before:absolute before:content-[''] before:h-px before:w-full before:bg-[#dddce7] before:-translate-y-2/4 before:z-[-1] before:left-0 before:top-2/4">
                                        <p class="inline-block bg-[#FAFBFF] mb-0 px-[15px] py-0">OR</p>
                                    </div>
                                    <div class="block text-center">
                                        <p class="text-[#3b368c] text-base leading-[26px]">Sign up with your email</p>
                                        <NuxtLink to="#" class=" no-underline border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] transition-all duration-[ease] delay-[0.3s] mt-[9px] mb-[19px] px-[30px] py-2.5 rounded-[50px] border-solid border-[rgba(59,54,140,0.1)] hover:shadow-[2px_13px_16px_0px_rgba(59,54,140,0.1)]"><img src="assets/images/google.png" class="mr-2" alt=""> Sign Up with
                                            Google</NuxtLink>
                                        <p class="text-base">
                                            Don't have an account? <NuxtLink class="text-[#3b368c] font-semibold hover:underline" to="/peyamba/register">
                                                Sign up here
                                            </NuxtLink>
                                        </p>
                                    </div>
                                </form>
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

<style lang="scss" scoped></style>
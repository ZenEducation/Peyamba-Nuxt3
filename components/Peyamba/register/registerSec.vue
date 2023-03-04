<template>
    <div>
        <section class=" relative h-screen w-full">
            <div>
                <div class="container mx-auto sm:px-4 block">
                    <div class="flex flex-wrap mx-[-15px]">
                        <div class="lg:w-2/5 pr-4 pl-4 relative w-full">
                            <NuxtLink to="/peyamba" class="text-white px-0 py-[15px]  hover:underline"><i
                                    class="fas fa-chevron-left mr-[5px]"></i> Back to peyamba</NuxtLink>
                        </div>
                        <div class="lg:w-3/5 pr-4 pl-4 ">
                            <div class="block text-left px-0 py-[15px]">
                                <img src="@/assets/frontend/images/logo2.png" class="inline-block" alt="logo">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container  sm:px-4">
                <div class="flex flex-wrap  justify-end mx-[-15px]">
                    <div class="bg-[url('@/assets/frontend/images/reg.jpg')] lg:w-2/5 bg-no-repeat bg-center bg-cover h-screen w-[43%] block -z-1 absolute left-0 top-0">
                    </div>
                    
                    <div class="lg:w-3/5 pr-4 pl-4  relative w-full">
                        <div class="h-[calc(100vh_-_72px)] overflow-y-auto pr-10 pt-[30px] pb-10">
                            <div class="text-left">
                                <h2 class="uppercase text-[#3b368c] text-[50px] leading-[60px] font-bold block mb-[11px]">
                                    Welcome to PEYAMBA
                                </h2>
                                <p class="text-[#3b368c] text-[18px]">
                                    Let's create your profile! Just fill in the fields below, and
                                    we’ll get a new account.
                                </p>
                            </div>
                            <div>
                                <form action="#">
                                    <h4 class="text-2xl leading-[34px] text-[#3b368c] font-bold mb-[25px]">Acount Details</h4>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Username*</label>
                                        <input type="text" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]" placeholder="Enter Your Usewrname">
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Email Address*</label>
                                        <input type="email" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]" placeholder="Enter Your Email">
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Password*</label>
                                        <input type="text" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]" placeholder="Enter Your Password">
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Confirm Password*</label>
                                        <input type="text" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]" placeholder="Enter Your Password">
                                    </div>
                                    <h4 class="content-title mt-5">Profile Details</h4>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Name*</label>
                                        <input type="text" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]" placeholder="Enter Your Full Name">
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Birthday*</label>
                                        <input type="date" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]">
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">I am a*</label>
                                        <div class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] flex flex-wrap items-center h-[60px] justify-center rounded-[5px] border-solid border-[rgba(59,54,140,0.1)]">
                                            <div class="mr-3">
                                                
                                                <input type="radio" name="gender1" id="males1" class="w-5 h-5 border rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="males1" class=" ml-2">Man</label>
                                            </div>
                                            <div>
                                                
                                                <input type="radio" name="gender1" id="females1" class="w-5 h-5 border rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="females1" class=" ml-2">Woman</label>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Looking for a*</label>
                                        <div class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] flex flex-wrap items-center h-[60px] justify-center rounded-[5px] border-solid border-[rgba(59,54,140,0.1)]">
                                            <div class="mr-3">
                                                
                                                <input type="radio" name="gender2" id="males" class="w-5 h-5 border rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="males" class=" ml-2">Man</label>
                                            </div>
                                            <div>
                                                
                                                <input type="radio" name="gender2" id="females" class="w-5 h-5 border rounded-[50%] border-solid border-[#5650ce] hover:shadow-[0_0_5px_0px_#5650ce_inset] before:content-[''] before:block before:w-3/5 before:h-3/5 before:mx-auto before:my-[20%] before:rounded-[50%] checked:before:bg-[#5650ce] checked:bg-[#5650ce]" ><label for="females" class=" ml-2">Woman</label>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">Marial status*</label>
                                        <div class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] flex flex-wrap items-center h-[60px] justify-center rounded-[5px] border-solid border-[rgba(59,54,140,0.1)]">
                                            <div class="w-full h-full">
                                                <select class="bg-transparent w-full h-full leading-[60px] border-[none]">
                                                    <option value="" class="text-[#222] leading-5 h-auto shadow-none bg-white px-2.5 py-0 border-0">Single</option>
                                                    <option value="" class="text-[#222] leading-5 h-auto shadow-none bg-white px-2.5 py-0 border-0">Marid</option>
                                                    <option value="" class="text-[#222] leading-5 h-auto shadow-none bg-white px-2.5 py-0 border-0">Marid</option>
                                                    <option value="" class="text-[#222] leading-5 h-auto shadow-none bg-white px-2.5 py-0 border-0">Marid</option>
                                                </select>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="mb-4">
                                        <label for="" class="text-lg leading-7 text-[#3b368c] font-semibold">City*</label>
                                        <input type="text" class="border bg-[rgb(234,242,252)] shadow-[1.948px_13.864px_6px_0px_rgba(220,234,251,0.3)] text-base text-[#3b368c] h-[60px] px-[30px] py-0 border-solid border-[rgba(59,54,140,0.1)] placeholder-[#3b368c]" placeholder="Enter Your City">
                                    </div>
                                    <button class="mt-5 px-10 py-4 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] font-semibold text-white inline-block cursor-pointer w-auto h-auto rounded-[50px] border-0 hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)] focus:outline-0" data-toggle="modal" data-target="#email-confirm">Create
                                        Your
                                        Profile</button>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>

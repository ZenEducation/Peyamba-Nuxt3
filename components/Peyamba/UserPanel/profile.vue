<template>
    <div>
        <section class="user-setting-section px-0 py-[50px]">
            <div class="container mx-auto sm:px-4">
                <div class="flex flex-wrap ">
                    <div class="xl:w-1/3  md:w-2/5 pr-4 pl-4">

                        <div class="bg-[#f6f4f9] shadow-[2.736px_-7.518px_57px_0px_rgba(119,123,146,0.18)] overflow-hidden rounded-[10px]" id="accordionExample">
                            <div class="bg-[none] rounded-none border-0">
                                <div class="mb-0 p-0 rounded-none border-b-[rgba(0,0,0,0.1)] border-b border-solid" id="headingOne">
                                    <button class="flex font-bold items-center text-xl relative pl-5 pr-10 py-10 rounded-none border-0 focus:outline-0" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true"
                                        aria-controls="collapseOne">
                                        <div class="w-10 h-10  bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] leading-10 text-center text-base mr-5 rounded-[50%]">
                                            <i class="fas fa-user text-[#f6e9f9]  bg-transparent"></i>
                                        </div>
                                        <span class="flex-[1]">My Profile</span>
                                        <div class="absolute text-xs text-center -translate-y-2/4 w-5 h-5 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-white rounded-[50%] right-5 top-2/4">
                                            <i class="fas fa-plus hidden leading-5"></i>
                                            <i class="fas fa-minus block leading-5"></i>
                                        </div>
                                    </button>
                                </div>

                                <div id="collapseOne" class="show visible" aria-labelledby="headingOne"
                                    data-parent="#accordionExample">
                                    <div>
                                        <ul type="disc">
                                            <li>
                                                <NuxtLink class="text-sm  font-bold transition-all duration-[ease] delay-[0.3s] active text-[#ff3366] hover:text-[#ff3366]" to="user-setting.html">Profile Info</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]  hover:text-[#ff3366]" to="user-notification.html">Notifications</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]  hover:text-[#ff3366]" to="user-friend-request.html">Friend Requests</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]  hover:text-[#ff3366]" to="user-badges.html">Badges</NuxtLink>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                            <div class="bg-[none] rounded-none border-0">
                                <div class="mb-0 p-0 rounded-none border-b-[rgba(0,0,0,0.1)] border-b border-solid" id="headingTwo">
                                    <button class="collapsed text-left flex font-bold items-center text-xl relative pl-5 pr-10 py-10 rounded-none border-0 focus:outline-0" type="button" data-toggle="collapse"
                                        data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                        <div class="w-10 h-10 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] leading-10 text-center text-base mr-5 rounded-[50%]">
                                            <i class="fas fa-cogs text-[#f6e9f9] bg-transparent"></i>
                                        </div>
                                        <span class="flex-[1]">
                                            Account
                                        </span>
                                        <div class="absolute text-xs text-center -translate-y-2/4 w-5 h-5 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-white rounded-[50%] right-5 top-2/4">
                                            <i class="fas fa-plus block leading-5"></i>
                                            <i class="fas fa-minus hidden leading-5"></i>
                                        </div>
                                    </button>
                                </div>
                                <div id="collapseTwo" class="collapse hidden" aria-labelledby="headingTwo"
                                    data-parent="#accordionExample">
                                    <div>
                                        <ul>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-account-info.html">Account Info</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-change-pass.html">Change Password</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-privicy-setting.html">Privacy Settings</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-verify-account.html">Verified account</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-close-account.html">Close Account</NuxtLink>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                            <div class="bg-[none] rounded-none border-0">
                                <div class="mb-0 border-b-0 p-0 rounded-none border-b-[rgba(0,0,0,0.1)] border-solid" id="headingThree">
                                    <button class="collapsed text-left flex font-bold items-center text-xl relative pl-5 pr-10 py-10 rounded-none border-0 focus:outline-0" type="button" data-toggle="collapse"
                                        data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                        <div class="w-10 h-10 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] leading-10 text-center text-base mr-5 rounded-[50%]">
                                            <i class="far fa-credit-card text-[#f6e9f9] bg-transparent "></i>
                                        </div>
                                        <span class="flex-[1]">
                                            Subscriptions & Payments
                                        </span>
                                        <div class="absolute text-xs text-center -translate-y-2/4 w-5 h-5 bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-white rounded-[50%] right-5 top-2/4">
                                            <i class="fas fa-plus block leading-5"></i>
                                            <i class="fas fa-minus hidden leading-5"></i>
                                        </div>
                                    </button>
                                </div>
                                <div id="collapseThree" class="collapse hidden" aria-labelledby="headingThree"
                                    data-parent="#accordionExample">
                                    <div>
                                        <ul>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-billing.html">Billing & Payout</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-plan.html">Upgrade Membership Plan</NuxtLink>
                                            </li>
                                            <li>
                                                <NuxtLink class="text-sm text-[#3e3f5e] font-bold transition-all duration-[ease] delay-[0.3s]" to="user-purchase.html">View Purchase History</NuxtLink>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                    <div class="xl:w-2/3  md:w-3/5 pr-4 pl-4 ">
                        <div class="shadow-[0px_0px_40px_0px_rgba(94,92,154,0.12)] text-2xl leading-[34px] font-bold bg-white flex justify-between mb-[30px] p-[30px] rounded-[5px]">
                            Profile Info
                        </div>
                        <div class="flex flex-wrap ">
                            <div class="lg:w-1/2 pr-4 pl-4">
                                <div class="bg-white shadow-[0px_10px_5px_0px_rgba(119,123,146,0.02)] transition-all duration-[ease] delay-[0.3s] rounded-[10px]">
                                    <div class="h-40 bg-[url('@/assets/frontend/images/profile/profile-box-bg.png')] bg-no-repeat bg-[bottom_center] bg-contain"></div>
                                    <div class="relative text-center pt-[55px] pb-[30px] px-[30px]">
                                        <div class="bg-white w-[120px] h-[120px] absolute -translate-x-2/4 top-[-60px] z-[9] rounded-[50%] left-2/4 before:absolute before:content-[''] before:w-[140px] before:h-[140px] before:bg-[rgba(255,255,255,0.2)] before:z-[-1] before:rounded-[50%] before:-left-2.5 before:-top-2.5 after:absolute after:content-[''] after:w-40 after:h-40 after:bg-[rgba(255,255,255,0.2)] after:z-[-1] after:rounded-[50%] after:-left-5 after:-top-5">
                                            <img src="@/assets/frontend/images/profile/profile-user.png" class="rounded-[50%]" alt="">
                                            <div class="absolute w-5 h-5 bg-[#1ce36f] rounded-[50%] border-[3px] border-solid border-white right-[9px] bottom-[9px]"></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="lg:w-1/2 pr-4 pl-4">
                                <div class="mb-30 bg-white shadow-[0px_0px_40px_0px_rgba(94,92,154,0.12)] relative pl-[90px] pr-[30px] py-[30px] rounded-[5px]">
                                    <div class="absolute -translate-y-2/4 w-10 h-10 leading-10 text-center bg-[#f7e9f8] mr-5 rounded-[50%] left-[30px] top-2/4">
                                        <i class="fas fa-user bg-clip-text bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] fill-transparent"></i>
                                    </div>
                                    <div class="block">
                                        <h4 class="text-sm m-0">
                                            Change Avatar
                                        </h4>
                                        <span class="text-sm text-[#9192a6] mb-0">
                                            120x120p size minimum
                                        </span>
                                    </div>
                                </div>
                                <div class="mb-30 bg-white shadow-[0px_0px_40px_0px_rgba(94,92,154,0.12)] relative pl-[90px] pr-[30px] py-[30px] rounded-[5px]">
                                    <div class="absolute -translate-y-2/4 w-10 h-10 leading-10 text-center bg-[#f7e9f8] mr-5 rounded-[50%] left-[30px] top-2/4">
                                        <i class="fas fa-image bg-clip-text bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] fill-transparent"></i>
                                    </div>
                                    <div class="block">
                                        <h4 class=" text-sm m-0">
                                            Change Cover
                                        </h4>
                                        <span class="text-sm text-[#9191a6] mb-0">
                                            1200x300p size minimum
                                        </span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="mt-30">
                            <div>
                                About your Profile
                            </div>
                            <div>
                                <div class="flex flex-wrap ">
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Profile Name</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="text" placeholder="Profile Name">
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Public Email</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="text" placeholder="Public Email">
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name=""
                                                placeholder="Write a little description about you..."></textarea>
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Country</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="" disabled selected>Select Country</option>
                                                <option value="">United State</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">City</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="" disabled selected>Select City</option>
                                                <option value="">New Work</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Birthday</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="date">
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Occupation</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="text" placeholder="Occupation">
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Status</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="">In a Relationship</option>
                                                <option value="">Single</option>
                                                <option value="">Marid</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Birthplace</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="text" placeholder="Birthplace">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="mt-30">
                            <div>
                                Interests
                            </div>
                            <div>
                                <div class="flex flex-wrap ">
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class="mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Favourite TV Shows</label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" placeholder="Favourite TV Shows"></textarea>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Favourite Music Bands / Artists</label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" placeholder="Favourite Music Bands / Artists"></textarea>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Favourite Movies</label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" placeholder="Favourite Movies"></textarea>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Favourite Games </label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" placeholder="Favourite Games "></textarea>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Favourite Games </label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" placeholder="Favourite Games"></textarea>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="mt-30">
                            <div>
                                Jobs & Education
                            </div>
                            <div>
                                <div class="flex flex-wrap ">
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Title or Place</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="text" placeholder="Title or Place">
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Year Started</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="">2014</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Year End</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="">2017</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Description</label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" id="" placeholder="Description"></textarea>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Title or Place</label>
                                            <input class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" type="text" placeholder="Title or Place">
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Year Started</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="">2014</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-1/2 pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Year End</label>
                                            <select class="h-[60px] border px-5 py-0 border-solid border-[rgba(0,0,0,0.1)]" name="" id="">
                                                <option value="">2017</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="md:w-full pr-4 pl-4">
                                        <div class=" mb-[30px]">
                                            <label for="" class="text-sm text-[#505386] font-semibold mb-0">Description</label>
                                            <textarea class="border h-[120px] border-solid border-[rgba(0,0,0,0.1)]" name="" id="" placeholder="Description"></textarea>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="buttons  mt-30">
                            <button type="submit" class="inline-block w-auto bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] font-semibold text-white cursor-pointer h-auto px-[35px] py-[11px] rounded-[50px] border-0 hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)]">Save Changes</button>
                            <button class="inline-block font-semibold w-auto h-auto ml-5 px-[35px] py-[11px] rounded-[50px] border-2 border-solid border-[rgba(0,0,0,0.1)] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] text-white cursor-pointer  hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)]">Discard All</button>
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
<template>
    <div>
        <section class="product-category px-0 py-[120px]">
            <div class="container mx-auto sm:px-4">
                <div class="flex flex-wrap ">

                    <div class="lg:w-1/4 pr-4 pl-4 product-md-grid">


                        <div
                            class=" bg-white border mb-[30px] rounded-[5px] border-solid border-[rgba(0,0,0,0.2)] last:mb-0 min-[576px]:mb-[30px]">
                            <div class="pb-[30px] rounded pt-[30px] px-[30px]">
                                <h6
                                    class="mb-[69px] font-medium capitalize text-2xl leading-[34px] pb-[15px] border-b-[rgba(0,0,0,0.2)] border-b border-solid">
                                    Filter by Price</h6>
                                <div class="text-center">
                                    <div id="slider"></div>

                                    <div class=" flex justify-between mt-5 mb-[13px]">
                                        <div class=" text-sm font-semibold text-[#777]">
                                            Price:
                                        </div>
                                        <div class="text-sm font-semibold text-[#333]">
                                            $0-$1000
                                        </div>
                                    </div>
                                    <NuxtLink to="#"
                                        class="text-base font-semibold uppercase px-5 py-[3px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] shadow-[0.872px_9.962px_20px_0px_rgba(12,78,165,0.3)] text-white inline-block cursor-pointer w-auto h-auto rounded-[50px] border-0 hover:text-white hover:shadow-[1px_10px_20px_0px_rgba(12,78,165,0.43)]">
                                        Filter</NuxtLink>
                                </div>
                            </div>
                        </div>
                        <div
                            class=" bg-white border mb-[30px] rounded-[5px] border-solid border-[rgba(0,0,0,0.2)] min-[576px]:mb-[30px]">
                            <div class="border-[none] rounded pt-[30px] pb-[33px] px-[30px]">
                                <h6
                                    class="font-medium capitalize text-2xl leading-[34px] mb-[22px] pb-[15px] border-b-[rgba(0,0,0,0.2)] border-b border-solid">
                                    Gender</h6>
                                <div class="mb-[-15px]">
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="men"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="men"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Men
                                            (30)</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="women"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none "><label
                                            for="women"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Women
                                            (25)</label>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-white border mb-[30px] rounded-[5px] border-solid border-[rgba(0,0,0,0.2)] min-[576px]:mb-[30px]">
                            <div class="border-[none] rounded pt-[30px] pb-[33px] px-[30px]">
                                <h6
                                    class="font-medium capitalize text-2xl leading-[34px] mb-[22px] pb-[15px] border-b-[rgba(0,0,0,0.2)] border-b border-solid">
                                    Categories</h6>
                                <div class="mb-[-15px]">
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="c1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="c1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Jewelry
                                            &
                                            Accessories</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="c2"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="c2"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Rings</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="c3"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="c3"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Watches</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="c4"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="c4"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Consumer
                                            Electronics</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="c5"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="c5"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Gift
                                            item</label>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-white border mb-[30px] rounded-[5px] border-solid border-[rgba(0,0,0,0.2)] min-[576px]:mb-[30px]">
                            <div class="border-[none] rounded pt-[30px] pb-[33px] px-[30px]">
                                <h6
                                    class="font-medium capitalize text-2xl leading-[34px] mb-[22px] pb-[15px] border-b-[rgba(0,0,0,0.2)] border-b border-solid">
                                    Color</h6>
                                <div class="mb-[-15px]">
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="r1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="r1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Blue
                                            (11)</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="r2"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="r2"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Black
                                            (5)</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="r3"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="r3"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Pink
                                            (4)</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="r4"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="r4"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Multi-Coloured
                                            (3)</label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="r5"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="r5"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">Yellow
                                            (2)</label>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-white border mb rounde-0 d-[5px] border-solid border-[rgba(0,0,0,0.2)] min-[576px]:mb-[30px]">
                            <div class="border-[none] rounded pt-[30px] pb-[33px] px-[30px]">
                                <h6
                                    class="font-medium capitalize text-2xl leading-[34px] mb-[22px] pb-[15px] border-b-[rgba(0,0,0,0.2)] border-b border-solid">
                                    Rating</h6>
                                <div class="mb-[-15px]">
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="s1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="s1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">
                                            <span class="mr-[20px]">
                                                5 star(9)
                                            </span>
                                            <span>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                            </span>
                                        </label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="s1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="s1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">
                                            <span class="mr-[20px]">
                                                4 star(9)
                                            </span>
                                            <span>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                            </span>
                                        </label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="s1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="s1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">
                                            <span class="mr-[20px]">
                                                3 star(9)
                                            </span>
                                            <span>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                            </span>
                                        </label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="s1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="s1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">
                                            <span class="mr-[20px]">
                                                2 star(9)
                                            </span>
                                            <span>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                            </span>
                                        </label>
                                    </div>
                                    <div class="mb-[5px] flex flex-wrap items-center">
                                        <input type="checkbox" name="mode" id="s1"
                                            class="w-3.5 h-3.5 box-border border text-[#1c2386] rounded overflow-visible text-[100%] leading-[1.15] m-0 p-0 border-solid border-[#2d4186] outline-none"><label
                                            for="s1"
                                            class="w-[calc(100%_-_14px)] relative text-sm font-semibold cursor-pointer m-0 pl-2.5">
                                            <span class="mr-[20px]">
                                                1 star(9)
                                            </span>
                                            <span>
                                                <i
                                                    class="fas fa-star text-xs mr-[-3px] text-[#f87115] font-black font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                                <i
                                                    class="far fa-star text-xs mr-[-3px] text-[#f87115] font-normal font-['Font_Awesone_5_Free']"></i>
                                            </span>
                                        </label>
                                    </div>

                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:w-3/4 pr-4 pl-4 ">
                        <div class="flex flex-wrap ">
                            <div class="lg:w-full pr-4 pl-4">
                                <div
                                    class="border relative bg-white mb-[30px] px-[38px] py-2.5 rounded-[5px] border-solid border-[rgba(0,0,0,0.2)]">
                                    <div class="flex flex-wrap justify-between items-center">

                                        <ul class="flex flex-wrap justify-center items-center m-0 p-0 list-none"
                                            role="tablist">
                                            <li id="gird-view">
                                                <NuxtLink
                                                    class="border w-[60px] h-10 leading-10 text-center cursor-pointer text-lg text-[#ff3366] transition-all duration-[ease] delay-[0.3s] inline-block bg-transparent no-underline mr-5 p-0 rounded-[20px] border-solid border-[rgba(0,0,0,0.1)]"
                                                    id="pills-gird-tab" data-toggle="pill" to="#pills-gird" role="tab"
                                                    aria-controls="pills-gird" aria-selected="true">
                                                    <i class="fas fa-th"></i>
                                                </NuxtLink>

                                            </li>
                                            <li id="list-view" class="mr-0">
                                                <NuxtLink
                                                    class="border w-[60px] h-10 leading-10 text-center cursor-pointer text-lg text-[#333333] transition-all duration-[ease] delay-[0.3s] inline-block bg-transparent no-underline mr-5 p-0 rounded-[20px] border-solid border-[rgba(0,0,0,0.1)]"
                                                    id="pills-list-tab" data-toggle="pill" to="#pills-list" role="tab"
                                                    aria-controls="pills-list" aria-selected="false">
                                                    <i class="fas fa-bars"></i>
                                                </NuxtLink>

                                            </li>
                                        </ul>
                                        <div class="flex flex-wrap items-center">
                                            <div class="flex flex-wrap items-center mr-[30px]">
                                                <span class="opacity-100 block mr-5">Show :</span>
                                                <select
                                                    class="h-10 border bg-transparent px-5 py-0 rounded-[20px] border-solid border-[rgba(0,0,0,0.11)]">
                                                    <option value="12"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        12
                                                    </option>
                                                    <option value="15"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        15
                                                    </option>
                                                    <option value="18"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        18
                                                    </option>
                                                    <option value="21"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        21
                                                    </option>
                                                    <option value="24"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        24
                                                    </option>
                                                    <option value="27"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        27
                                                    </option>
                                                    <option value="30"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        30
                                                    </option>
                                                </select>
                                            </div>
                                            <div>
                                                <span class="opacity-100 block mr-5">Sort By :</span>
                                                <select
                                                    class="h-10 border bg-transparent px-5 py-0 rounded-[20px] border-solid border-[rgba(0,0,0,0.11)]">
                                                    <option value="showing"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        New
                                                    </option>
                                                    <option value="exclusive"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        exclusive
                                                    </option>
                                                    <option value="trending"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        trending
                                                    </option>
                                                    <option value="most-view"
                                                        class="max-h-[150px] overflow-y-auto bg-[#fafbff] border text-[#333333] border-solid border-[rgba(163,177,198,0.151)] hover:bg-transparent">
                                                        most view
                                                    </option>
                                                </select>
                                            </div>
                                            <div
                                                class="w-10 h-10 text-center leading-10 text-white text-base bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] inline-block cursor-pointer rounded-[50%]">
                                                <i class="fas fa-search"></i>
                                            </div>
                                        </div>
                                    </div>

                                    <div
                                        class="absolute w-full z-[9] bg-white rounded shadow-[0px_0px_15px_rgba(0,0,0,0.1)] hidden p-2.5 left-0 top-full">
                                        <input type="text" placeholder="Enter Your Text hear"
                                            class="h-10 border text-base border-solid border-[rgba(0,0,0,0.2)]" />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="tab-content" id="pills-tabContent">
                            <div class="block transition-opacity duration-[0.15s] ease-linear" id="pills-gird"
                                role="tabpanel" aria-labelledby="pills-gird-tab">
                                <div class="flex flex-wrap ">
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 md:w-1/2 pr-4 pl-4">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                    <div class="lg:w-1/3 md:w-1/2 pr-4 pl-4">
                                        <div class="group">
                      <div
                        class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                        <div class="relative overflow-hidden">
                          <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                            class="group-hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                          <span
                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                          <ul
                            class="group-hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                            <li class="border-b-[rgba(0,0,0,0.1)] border-b-0 border-solid">
                              <NuxtLink to="#" class="block">
                                <i
                                  class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm"></i>
                              </NuxtLink>
                            </li>
                          </ul>
                        </div>
                        <div class="relative pt-[62px] pb-[30px] px-[30px]">
                          <span
                            class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center absolute top-[-30px] rounded-[50%] right-2.5">
                            $15
                          </span>
                          <h4 class="text-2xl leading-[34px] block font-semibold">
                            Butterfly Rings
                          </h4>
                          <div class="flex">
                            <div>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                              <i class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                            </div>
                            <span class="text-[15px] mx-2.5 my-0"> | </span>
                            <span class="text-sm relative top-0.5">
                              229 review
                            </span>
                          </div>
                          <NuxtLink
                            class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute  before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                            to="/peyamba/singleshope"><span
                              class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                              Now</span></NuxtLink>
                        </div>
                      </div>
                    </div>
                                    </div>
                                </div>
                            </div>
                            <div class="opacity-100 hidden" id="pills-list" role="tabpanel"
                                aria-labelledby="pills-list-tab">
                                <div class="flex flex-wrap ">
                                    <div class="lg:w-full pr-4 pl-4">
                                        <div class="flex flex-wrap mx-[-15px]">
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="flex-[100%] max-w-full px-[15px]">
                                                <div
                                                    class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)]">
                                                    <div class="relative overflow-hidden">
                                                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                                                            class="transition-all duration-[ease] delay-[0.3s] w-full align-middle border-none;
    }
    " alt="">
                                                        <span
                                                            class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                                                        <ul class="absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgb(0_0_0_/_20%)] transition-all duration-[ease] delay-[0.3s] m-0 px-2.5 py-[3px] rounded-[5px] top-[30px]">
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-sliders-h bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px] border-b-[rgba(0,0,0,0.1)] border-b border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="fas fa-heart bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                            <li class="px-0 py-[5px]  border-b-0 border-solid list-none">
                                                                <NuxtLink to="#" class="block transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline">
                                                                    <i class="far fa-eye bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-sm inline-block not-italic leading-none font-black font-['Font_Awesome_5_Free']"></i>
                                                                </NuxtLink>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                    <div class="relative flex-[1] pl-[60px] pr-[30px] py-[30px]">
                                                        <div class="flex h-full">
                                                            <div class="flex-[1] self-center">
                                                                <span
                                                                    class="w-[60px] h-[60px] bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] block text-white font-bold text-2xl leading-[60px] text-center left-[-30px] absolute rounded-[50%] top-[30px]">
                                                                    $15
                                                                </span>
                                                                <h4
                                                                    class="text-2xl leading-[34px] block font-semibold text-[#333333] m-0 font-['Fira_Sans','sans_serif']">
                                                                    Butterfly Rings
                                                                </h4>
                                                                <div class="flex">
                                                                    <div>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                        <i
                                                                            class="fas fa-star text-xs text-[#f87115] -mr-1"></i>
                                                                    </div>
                                                                    <span class="text-[15px] mx-2.5 my-0">
                                                                        |
                                                                    </span>
                                                                    <span class="text-sm relative top-0.5">
                                                                        229 review
                                                                    </span>
                                                                </div>

                                                                <NuxtLink to="#" class="add-wish-btn block text-[#333] text-base transition-all duration-[ease] delay-[0.3s] bg-transparent no-underline mt-[19px] mb-0">
                                                                    <i class="fas fa-heart text-[#f87115] text-lg font-black inline-block not-italic leading-none mr-1 font-['Font_Awesome_5_Free']"></i> Add to wish list
                                                                </NuxtLink>
                                                            </div>
                                                            <div class="w-[170px] text-center h-full pl-[30px] pr-0 py-0 border-l-[rgba(0,0,0,0.2)] border-l border-solid">
                                                                <NuxtLink class="block w-[200px] h-10 leading-10 text-lg no-underline text-[#56585a] relative transition-all duration-[0.4s] text-center before:absolute before:content-['\f30b'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 before:font-['Font_Awesome_5_Free']" to="/peyamba/singleshope">
                                                                    <span class=" pl-[20px] relative z-[1] uppercase ">Buy Now</span>
                                                                </NuxtLink>
                                                                <NuxtLink to="#" class="text-sm leading-6 uppercase font-semibold text-[#333] transition-all duration-[ease] delay-[0.3s] bg-transparent mt-6 border-b-[#a5a5a5] border-b border-solid border-[none]">More Info</NuxtLink>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="flex flex-wrap ">
                            <div class="lg:w-full pr-4 pl-4">
                                <div class="pagination-area text-center">
                                    <NuxtLink to="#"><i class="fas fa-angle-double-left"></i><span></span></NuxtLink>
                                    <NuxtLink to="#">1</NuxtLink>
                                    <NuxtLink to="#">2</NuxtLink>
                                    <NuxtLink to="#" class="active">3</NuxtLink>
                                    <NuxtLink to="#">4</NuxtLink>
                                    <NuxtLink to="#">5</NuxtLink>
                                    <NuxtLink to="#"><i class="fas fa-angle-double-right"></i></NuxtLink>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    </section>
</div></template>

<script setup>

</script>

<style lang="scss" scoped></style>
<template>
  <div>
    <section class="px-0 py-[120px]">
      <div class="container mx-auto sm:px-4">
        <div class="flex flex-wrap">
          <div class="lg:w-full pr-4 pl-4">
            <div class="flex flex-wrap">
              <div class="lg:w-full pr-4 pl-4">
                <div
                  class="border relative bg-white mb-[30px] px-[38px] py-2.5 rounded-[5px] border-solid border-[rgba(0,0,0,0.2)]">
                  <div class="flex flex-wrap justify-between items-center">
                    <ul class="flex flex-wrap list-none pl-0 mb-0 justify-end items-center" role="tablist">
                      <li id="gird-view">
                        <NuxtLink
                          class="active border w-[60px] h-10 leading-10 text-center cursor-pointer text-lg text-[#ff3366] mr-5 p-0 rounded-[20px] border-solid border-[rgba(0,0,0,0.1)]"
                          id="nav-gird-tab" data-toggle="tab" to="#nav-gird" role="tab" aria-controls="nav-gird"
                          aria-selected="true">
                          <i class="fas fa-th"></i>
                        </NuxtLink>
                      </li>
                      <li id="list-view" class="mr-0">
                        <NuxtLink
                          class="border w-[60px] h-10 leading-10 text-center cursor-pointer text-lg text-[#333333] mr-5 p-0 rounded-[20px] border-solid border-[rgba(0,0,0,0.1)]"
                          id="nav-list-tab" data-toggle="tab" to="#nav-list" role="tab" aria-controls="nav-list"
                          aria-selected="false">
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
            <div>
              <div class="opacity-100 block active" id="nav-gird" role="tabpanel" aria-labelledby="nav-gird-tab">
                <div class="flex flex-wrap">
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="img relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                          class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute before:content-['\f30b'] font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                          to="/peyamba/singleshope"><span
                            class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                            Now</span></NuxtLink>
                      </div>
                    </div>
                  </div>
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/02.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                          class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute before:content-['\f30b'] font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                          to="/peyamba/singleshope"><span
                            class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                            Now</span></NuxtLink>
                      </div>
                    </div>
                  </div>
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/03.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/04.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/05.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/06.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                          class="block w-[200px] h-10 leading-10 no-underline text-center relative transition-all duration-[0.4s] before:absolute before:content-['\f30b']  font-['Font_Awesome_5_Free'] before:font-black before:w-10 before:h-10 before:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] before:transition-all before:duration-[0.4s] before:leading-10 before:text-center before:text-xl before:text-white before:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] before:rounded-[50px] before:left-0 before:top-0 hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:shadow-[0px_3px_5px_0px_rgba(162,44,202,0.3)] hover:rounded-[50px] hover:before:w-full hover:before:text-right hover:before:bg-[none] hover:before:pr-5 text-base font-bold uppercase text-[#56585a] mt-6"
                          to="/peyamba/singleshope"><span
                            class="font-16-semibold relative z-[1] uppercase hover:left-[-15px] hover:text-white">Buy
                            Now</span></NuxtLink>
                      </div>
                    </div>
                  </div>
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/07.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/08.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/09.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/10.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/11.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                  <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
              <div class="tab-pane opacity-100" id="nav-list" role="tabpanel" aria-labelledby="nav-list-tab">
                <div class="flex flex-wrap">
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/02.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/03.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/04.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/05.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/06.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/07.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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
                  <div class="xl:w-1/2 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                    <div
                      class="border overflow-hidden bg-white transition-all duration-[ease] delay-[0.3s] flex self-center mb-[30px] rounded-[10px] border-solid border-[rgba(0,0,0,0.2)] hover:border-[#5b3acc]">
                      <div class="relative overflow-hidden">
                        <img src="@/assets/frontend/images/shoping/ShopPage_01/08.jpg"
                          class="hover:scale-110 transition-all duration-[ease] delay-[0.3s] w-full" alt="" />
                        <span
                          class="absolute bg-[#5b3acc] text-xs leading-3 text-white uppercase pt-1.5 pb-1 px-[15px] rounded-[0px_50px_50px_0px] left-0 top-[30px]">Sale</span>
                        <ul
                          class="hover:right-5 absolute right-[-50px] bg-[rgba(255,255,255,0.9)] shadow-[0px_0px_5px_0px_rgba(0,0,0,0.2)] transition-all duration-[ease] delay-[0.3s] px-2.5 py-[3px] rounded-[5px] top-[30px]">
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
                      <div class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
                        <span class="relative flex-[1] self-center pl-[60px] pr-[30px] py-[30px]">
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

            <div class="flex flex-wrap">
              <div class="lg:w-full pr-4 pl-4">
                <div class="text-lg mr-[-15px] ml-[-15px] my-0 text-center">
                  <NuxtLink to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)]">
                    <i class="fas fa-angle-double-left"></i><span></span></NuxtLink>
                  <NuxtLink to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline">
                    1</NuxtLink>
                  <NuxtLink to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline">
                    2</NuxtLink>
                  <NuxtLink to="#"
                    class="shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] text-white no-underline">
                    3</NuxtLink>
                  <NuxtLink to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline">
                    4</NuxtLink>
                  <NuxtLink to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline">
                    5</NuxtLink>
                  <NuxtLink to="#"
                    class="text-[#333] bg-white shadow-[0px_15px_30px_0px_rgba(119,123,146,0.2)] w-[50px] h-[50px] leading-[50px] mx-0.5 my-0 rounded-[50%] hover:text-white hover:bg-[-o-linear-gradient(284deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] hover:bg-[linear-gradient(166deg,rgb(242,40,118)_0%,rgb(148,45,217)_100%)] no-underline">
                    <i class="fas fa-angle-double-right"></i></NuxtLink>
                </div>
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

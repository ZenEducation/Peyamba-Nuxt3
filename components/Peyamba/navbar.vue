<template>
  <div>
    <header
      class="fixed w-full z-[99] px-0 py-2.5 border-b border-solid border-[rgba(255,255,255,0.102)] left-0 top-0"
    >
      <div class="container mx-auto sm:px-4">
        <div class="header-wrapper flex flex-wrap justify-between items-center">
          <div class="w-[170px]">
            <NuxtLink to="/peyamba" class="inline-block">
              <img
                src="@/assets/frontend/images/logo/logo.png"
                alt="logo"
                class="max-w-full"
              />
            </NuxtLink>
          </div>
          <ul
            class="menu min-[992px]:flex min-[992px]:flex-wrap min-[992px]:justify-end min-[992px]:items-center"
          >
            <li
              class="min-[992px]:relative min-[992px]:px-3 py-[5px] min-[992px]:hover:opacity-100 min-[992px]:hover:visible min-[992px]:hover:translate-y-0 min-[992px]:hover:block"
            >
              <NuxtLink
                to="#"
                class="active px-3 py-[5px] no-underline min-[992px]:text-[#e9eeff] min-[992px]:text-base min-[992px]:font-bold min-[992px]:uppercase min-[992px]:relative min-[992px]:before:w-[calc(100%_-_10px)] min-[992px]:before:h-0.5 min-[992px]:before:bg-white min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:transition-all min-[992px]:before:duration-[ease] min-[992px]:before:delay-[0.3s] min-[992px]:before:origin-left min-[992px]:before:scale-x-0 min-[992px]:before:top-[calc(100%_+_18px)] min-[992px]:hover:scale-x-100"
                >Home</NuxtLink
              >
              <ul
                class="submenu min-[992px]:absolute min-[992px]:bg-white min-[992px]:min-w-[240px] min-[992px]:shadow-[0px_0px_11.7px_1.3px_rgba(0,0,0,0.08)] min-[992px]:opacity-0 min-[992px]:invisible min-[992px]:transition-all min-[992px]:duration-[ease] min-[992px]:delay-[0.3s] min-[992px]:translate-y-[15px] min-[992px]:px-0 min-[992px]:py-5 min-[992px]:left-1.5 min-[992px]:top-full min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:-translate-y-full min-[992px]:before:w-0 min-[992px]:before:h-0 min-[992px]:before:border-t-transparent min-[992px]:before:border-b-[15px] min-[992px]:before:border-x-transparent min-[992px]:before:border-[10px] min-[992px]:before:border-solid min-[992px]:before:border-white min-[992px]:before:left-[15px] min-[992px]:before:top-0 "
              >
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba"
                    class="active min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Home One</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/index2"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Home Two</NuxtLink
                  >
                </li>
              </ul>
            </li>
            <li
              class="min-[992px]:relative min-[992px]:px-3 py-[5px] min-[992px]:hover:opacity-100 min-[992px]:hover:visible min-[992px]:hover:translate-y-0 min-[992px]:hover:block"
            >
              <NuxtLink
                to="/peyamba/community"
                class="px-3 py-[5px] no-underline min-[992px]:text-[#e9eeff] min-[992px]:text-base min-[992px]:font-bold min-[992px]:uppercase min-[992px]:relative min-[992px]:before:w-[calc(100%_-_10px)] min-[992px]:before:h-0.5 min-[992px]:before:bg-white min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:transition-all min-[992px]:before:duration-[ease] min-[992px]:before:delay-[0.3s] min-[992px]:before:origin-left min-[992px]:before:scale-x-0 min-[992px]:before:top-[calc(100%_+_18px)] min-[992px]:hover:scale-x-100"
                >Community</NuxtLink
              >
            </li>
            <li
              class="min-[992px]:relative min-[992px]:px-3 py-[5px] min-[992px]:hover:opacity-100 min-[992px]:hover:visible min-[992px]:hover:translate-y-0 min-[992px]:hover:block"
            >
              <NuxtLink
                to="/peyamba/membership"
                class="px-3 py-[5px] no-underline min-[992px]:text-[#e9eeff] min-[992px]:text-base min-[992px]:font-bold min-[992px]:uppercase min-[992px]:relative min-[992px]:before:w-[calc(100%_-_10px)] min-[992px]:before:h-0.5 min-[992px]:before:bg-white min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:transition-all min-[992px]:before:duration-[ease] min-[992px]:before:delay-[0.3s] min-[992px]:before:origin-left min-[992px]:before:scale-x-0 min-[992px]:before:top-[calc(100%_+_18px)] min-[992px]:hover:scale-x-100"
                >Membership</NuxtLink
              >
            </li>
            <li
              class="min-[992px]:relative min-[992px]:px-3 py-[5px] min-[992px]:hover:opacity-100 min-[992px]:hover:visible min-[992px]:hover:translate-y-0 min-[992px]:hover:block"
            >
              <NuxtLink
                to="/peyamba/shop"
                class="px-3 py-[5px] no-underline min-[992px]:text-[#e9eeff] min-[992px]:text-base min-[992px]:font-bold min-[992px]:uppercase min-[992px]:relative min-[992px]:before:w-[calc(100%_-_10px)] min-[992px]:before:h-0.5 min-[992px]:before:bg-white min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:transition-all min-[992px]:before:duration-[ease] min-[992px]:before:delay-[0.3s] min-[992px]:before:origin-left min-[992px]:before:scale-x-0 min-[992px]:before:top-[calc(100%_+_18px)] min-[992px]:hover:scale-x-100"
                >Shop</NuxtLink
              >
            </li>
            <li
              class="min-[992px]:relative min-[992px]:px-3 py-[5px] min-[992px]:hover:opacity-100 min-[992px]:hover:visible min-[992px]:hover:translate-y-0 min-[992px]:hover:block"
            >
              <NuxtLink
                to="#"
                class="px-3 py-[5px] no-underline min-[992px]:text-[#e9eeff] min-[992px]:text-base min-[992px]:font-bold min-[992px]:uppercase min-[992px]:relative min-[992px]:before:w-[calc(100%_-_10px)] min-[992px]:before:h-0.5 min-[992px]:before:bg-white min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:transition-all min-[992px]:before:duration-[ease] min-[992px]:before:delay-[0.3s] min-[992px]:before:origin-left min-[992px]:before:scale-x-0 min-[992px]:before:top-[calc(100%_+_18px)] min-[992px]:hover:scale-x-100"
                >pages</NuxtLink
              >
              <ul
                class="submenu min-[992px]:absolute min-[992px]:bg-white min-[992px]:min-w-[240px] min-[992px]:shadow-[0px_0px_11.7px_1.3px_rgba(0,0,0,0.08)] min-[992px]:opacity-0 min-[992px]:invisible min-[992px]:transition-all min-[992px]:duration-[ease] min-[992px]:delay-[0.3s] min-[992px]:translate-y-[15px] min-[992px]:px-0 min-[992px]:py-5 min-[992px]:left-1.5 min-[992px]:top-full min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:-translate-y-full min-[992px]:before:w-0 min-[992px]:before:h-0 min-[992px]:before:border-t-transparent min-[992px]:before:border-b-[15px] min-[992px]:before:border-x-transparent min-[992px]:before:border-[10px] min-[992px]:before:border-solid min-[992px]:before:border-white min-[992px]:before:left-[15px] min-[992px]:before:top-0"
              >
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/userpanel"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >User Panel</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/aboutus"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >About Us</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/communitysingle"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Community Single</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/members"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Members</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/shop2"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Shop sidebar</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/singleprofile"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Single Profile One</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/singleprofile2"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Single Profile Two</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/singleprofile3"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Single Profile Three</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/singleshope"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Shop Details</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/contact"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Contact</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/login"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Login</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/register"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Register</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/404error"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >404</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/503error"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >503</NuxtLink
                  >
                </li>
              </ul>
            </li>
            <li
              class="min-[992px]:relative min-[992px]:px-3 py-[5px] min-[992px]:hover:opacity-100 min-[992px]:hover:visible min-[992px]:hover:translate-y-0 min-[992px]:hover:block"
            >
              <a
                href="#"
                class="px-3 py-[5px] no-underline min-[992px]:text-[#e9eeff] min-[992px]:text-base min-[992px]:font-bold min-[992px]:uppercase min-[992px]:relative min-[992px]:before:w-[calc(100%_-_10px)] min-[992px]:before:h-0.5 min-[992px]:before:bg-white min-[992px]:before:absolute min-[992px]:before:content-[''] min-[992px]:before:transition-all min-[992px]:before:duration-[ease] min-[992px]:before:delay-[0.3s] min-[992px]:before:origin-left min-[992px]:before:scale-x-0 min-[992px]:before:top-[calc(100%_+_18px)] min-[992px]:hover:scale-x-100"
                >blog</a
              >
              <ul
                class="submenu min-[992px]:absolute min-[992px]:bg-white min-[992px]:min-w-[240px] min-[992px]:shadow-[0px_0px_11.7px_1.3px_rgba(0,0,0,0.08)] min-[992px]:opacity-0 min-[992px]:invisible min-[992px]:transition-all min-[992px]:duration-[ease] min-[992px]:delay-[0.3s] min-[992px]:translate-y-[15px] min-[992px]:px-0 min-[992px]:py-5 min-[992px]:left-1.5 min-[992px]:top-full min-[992px]:before:absolute min-[992px]:before:content-['s'] min-[992px]:before:-translate-y-full min-[992px]:before:w-0 min-[992px]:before:h-0 min-[992px]:before:border-t-transparent min-[992px]:before:border-b-[15px] min-[992px]:before:border-x-transparent min-[992px]:before:border-[10px] min-[992px]:before:border-solid min-[992px]:before:border-white min-[992px]:before:left-[15px] min-[992px]:before:top-0"
              >
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/blog"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Blog</NuxtLink
                  >
                </li>
                <li
                  class="min-[992px]:px-5 min-[992px]:py-0 min-[992px]:hover:translate-x-0"
                >
                  <NuxtLink
                    to="/peyamba/blogsingle"
                    class="min-[992px]:capitalize min-[992px]:font-semibold min-[992px]:flex min-[992px]:text-[#292929] min-[992px]:hover:text-[#5650ce] min-[992px]:hover:pl-2.5"
                    >Blog Single</NuxtLink
                  >
                </li>
              </ul>
            </li>
            <li class="separator mr-[7px]">
              <span class="min-[992px]:text-white">|</span>
            </li>
            <li>
              <div
                class="serch-icon min-[992px]:cursor-pointer min-[992px]:text-white"
              >
                <i
                  class="fas fa-search min-[992px]:text-white min-[992px]:text-base"
                ></i>
                <!-- <font-awesome-icon :icon="['fas', 'fa-search']" /> -->
              </div>
            </li>
            <li>
              <div class="language-select ml-2.5">
                <select class="select-bar">
                  <option value="">EN</option>
                  <option value="">IN</option>
                  <option value="">BN</option>
                </select>
              </div>
            </li>
            <li>
              <a href="#" class="min-[992px]:flex min-[992px]:items-center">
                <img src="@/assets/frontend/images/user-demo.png" alt="" />
              </a>
              <ul
                class="submenu min-[992px]:left-auto min-[992px]:right-0 min-[992px]:before:left-auto min-[992px]:before:right-[15px]"
              >
                <li>
                  <a href="#">Profile</a>
                </li>
                <li>
                  <a href="#">Logout</a>
                </li>
              </ul>
            </li>
          </ul>
          <div class="header-bar lg:hidden">
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
      </div>
    </header>
    <div class="search-overlay">
      <div class="absolute top-0 bottom-0 right-0 px-4 py-3">
        <i class="fas fa-times"></i>
      </div>
      <form action="#">
        <input type="text" placeholder="Write what you want.." />
      </form>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>

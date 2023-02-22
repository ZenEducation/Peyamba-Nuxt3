<template>
    <div>
        <header class="header-section">
        <div class="container mx-auto sm:px-4">
            <div class="header-wrapper">
                <div class="logo">
                    <NuxtLink to="/peyamba">
                        <img src="@/assets/frontend/images/logo/logo.png" alt="logo">
                    </NuxtLink>
                </div>
                <ul class="menu">
                    <li>
                        <NuxtLink to="#" class="active">Home</NuxtLink>
                        <ul class="submenu">
                            <li>
                                <NuxtLink to="/peyamba" class="active">Home One</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/index2">Home Two</NuxtLink>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <NuxtLink to="/peyamba/community">Community</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/peyamba/membership">Membership</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/peyamba/shop">Shop</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="#">pages</NuxtLink>
                        <ul class="submenu">
                            <li>
                                <NuxtLink to="/peyamba/userpanel">User Panel</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/aboutus">About Us</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/communitysingle">Community Single</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/members">Members</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/shop2">Shop sidebar</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/singleprofile">Single Profile One</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/singleprofile2">Single Profile Two</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/singleprofile3">Single Profile Three</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/singleshope">Shop Details</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/contact">Contact</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/login">Login</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/register">Register</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/404error">404</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/503error">503</NuxtLink>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <a href="#">blog</a>
                        <ul class="submenu">
                            <li>
                                <NuxtLink to="/peyamba/blog">Blog</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/blogsingle">Blog Single</NuxtLink>
                            </li>
                        </ul>
                    </li>
                    <li class="separator">
                        <span>|</span>
                    </li>
                    <li>
                        <div class="serch-icon">
                            <i class="fas fa-search"></i>
                            <!-- <font-awesome-icon :icon="['fas', 'fa-search']" /> -->
                        </div>
                    </li>
                    <li>
                        <div class="language-select">
                            <select class="select-bar">
                                <option value="">EN</option>
                                <option value="">IN</option>
                                <option value="">BN</option>
                            </select>
                        </div>
                    </li>
                    <li class="user-profile">
                        <a href="#">
                            <img src="@/assets/frontend/images/user-demo.png" alt="">
                        </a>
                        <ul class="submenu">
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
        <div class="absolute top-0 bottom-0 right-0 px-4 py-3"><i class="fas fa-times"></i></div>
        <form action="#">
            <input type="text" placeholder="Write what you want..">
        </form>
    </div>
    </div>
</template>

<script setup>
    
</script>

<style lang="scss" scoped>

</style>
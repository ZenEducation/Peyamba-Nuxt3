<template>
    <div>
        <section class="profile-section">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap  justify-center">
                <div class="xl:w-1/3  lg:w-2/5  md:w-3/5 pr-4 pl-4">
                    <div class="left-profile-area">
                        <div class="profile-about-box">
                            <div class="top-bg"></div>
                            <div class="p-inner-content">
                                <div class="profile-img">
                                    <img src="@/assets/frontend/images/profile/profile-user.png" alt="">
                                    <div class="active-online"></div>
                                </div>
                                <h5 class="name">
                                    Albert Don
                                </h5>
                                <ul class="p-b-meta-one">
                                    <li>
                                        <span>21 Years Old</span>
                                    </li>
                                    <li>
                                        <span> <i class="fas fa-map-marker-alt"></i>Paris,France</span>
                                    </li>
                                </ul>
                                <div class="p-b-meta-two">
                                    <div class="left">
                                        <div class="icon">
                                            <i class="far fa-heart"></i>
                                        </div> 257
                                    </div>
                                    <div class="right">
                                        <NuxtLink to="#" class="custom-button">
                                            <i class="fab fa-cloudversify"></i> Get Premium
                                        </NuxtLink>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="profile-meta-box">
                            <ul class="p-m-b">
                                <li>
                                    <NuxtLink to="#" data-toggle="modal" data-target="#usermessage">
                                        <i class="far fa-envelope"></i>
                                        <div class="number">04</div>
                                    </NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink to="#" data-toggle="modal" data-target="#usernotification">
                                        <i class="far fa-bell"></i>
                                        <div class="number">04</div>
                                    </NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink to="#">
                                        <i class="fas fa-cogs"></i>
                                    </NuxtLink>
                                </li>
                            </ul>
                        </div>
                        <div class="profile-uplodate-photo">
                            <h4 class="p-u-p-header">
                                <i class="fas fa-camera"></i> 21 Upload Photos
                            </h4>
                            <div class="p-u-p-list">
                                <div class="my-col">
                                    <div class="img">
                                        <img src="@/assets/frontend/images/profile/up1.jpg" alt="">
                                        <div class="overlay">
                                            <NuxtLink to="@/assets/frontend/images/profile/up1.jpg" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-col">
                                    <div class="img">
                                        <img src="@/assets/frontend/images/profile/up2.jpg" alt="">
                                        <div class="overlay">
                                            <NuxtLink to="@/assets/frontend/images/profile/up2.jpg" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-col">
                                    <div class="img">
                                        <img src="@/assets/frontend/images/profile/up3.jpg" alt="">
                                        <div class="overlay">
                                            <NuxtLink to="@/assets/frontend/images/profile/up3.jpg" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-col">
                                    <div class="img">
                                        <img src="@/assets/frontend/images/profile/up4.jpg" alt="">
                                        <div class="overlay">
                                            <NuxtLink to="@/assets/frontend/images/profile/up4.jpg" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-col">
                                    <div class="img">
                                        <img src="@/assets/frontend/images/profile/up5.jpg" alt="">
                                        <div class="overlay">
                                            <NuxtLink to="@/assets/frontend/images/profile/up5.jpg" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-col">
                                    <div class="img">
                                        <img src="@/assets/frontend/images/profile/up6.jpg" alt="">
                                        <div class="overlay">
                                            <NuxtLink to="@/assets/frontend/images/profile/up6.jpg" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="xl:w-2/5  lg:w-1/2 pr-4 pl-4">
                    <div class="profile-main-content">
                        <ul class="top-menu">
                            <li>
                                <NuxtLink to="/peyamba/singleprofile">
                                    Activity 
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/singleprofile2">
                                    Profile 
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/singleprofile3" class="active">
                                    Friends  
                                    <div class="num">04</div>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/profilenotfound">
                                    Groups 
                                    <div class="num">14</div>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="/peyamba/profilenotfound">
                                    Media 
                                    <div class="num">47</div>
                                </NuxtLink>
                            </li>
                        </ul>
                        <div class="profile-friends">
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend1.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        Erma Porter
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend2.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        Vicki Alvarez 
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend3.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        Opal Farmer 
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend4.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        May Hart 
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend5.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        Julia Salazar 
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend6.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        Joy Bailey 
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                            <div class="single-friend">
                                <img src="@/assets/frontend/images/profile/friend7.png" alt="">
                                <div class="content">
                                    <NuxtLink to="community-single.tw.html" class="name">
                                        Julie Dunn 
                                        <div class="isvarify">
                                            <i class="fas fa-check-circle"></i>
                                        </div>
                                    </NuxtLink>
                                    <p class="date">
                                        a month ago
                                    </p>
                                    <NuxtLink to="community-single.tw.html" class="connnect-btn">
                                        Connected
                                    </NuxtLink>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
                <div class="xl:w-1/4  lg:w-2/5  md:w-3/5 pr-4 pl-4">
                    <div class="profile-aside-area">
                        <div class="other-profile">
                            <div class="o-p-header">
                                <h6 class="title">
                                    You may like
                                </h6>
                            </div>
                            <div class="o-p-content">
                                <div class="p-u-p-list-slider owl-carousel">
                                    <div class="slider-item">
                                        <div class="p-u-p-list">
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img1.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img2.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img3.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img4.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img5.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img6.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img7.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img8.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="slider-item">
                                        <div class="p-u-p-list">
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img1.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img2.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img3.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img4.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img5.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img6.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img7.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                            <div class="my-col">
                                                <div class="img">
                                                    <img src="@/assets/frontend/images/profile/op-img8.png" alt="">
                                                    <NuxtLink to="#" class="light-box mfp-iframe"><i class="fas fa-plus"></i></NuxtLink>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="chat-request">
                            <div class="c-r-heading">
                                <h6 class="title">
                                    <i class="far fa-comments"></i> Chat Request
                                </h6>
                            </div>
                            <div class="c-r-content">
                                <div class="c-r-content-list">
                                    <div class="single-c-r">
                                        <div class="left">
                                            <img src="@/assets/frontend/images/profile/c-r-img1.png" alt="">
                                            <div class="active-online"></div>
                                        </div>
                                        <div class="right">
                                            <h4 class="title">
                                                laura maria
                                            </h4>
                                            <p>
                                                true love is...
                                            </p>
                                        </div>
                                    </div>
                                    <div class="single-c-r">
                                        <div class="left">
                                            <img src="@/assets/frontend/images/profile/c-r-img2.png" alt="">
                                            <div class="active-online"></div>
                                        </div>
                                        <div class="right">
                                            <h4 class="title">
                                                laura maria
                                            </h4>
                                            <p>
                                                true love is...
                                            </p>
                                        </div>
                                    </div>
                                    <div class="single-c-r">
                                        <div class="left">
                                            <img src="@/assets/frontend/images/profile/c-r-img3.png" alt="">
                                            <div class="active-online"></div>
                                        </div>
                                        <div class="right">
                                            <h4 class="title">
                                                laura maria
                                            </h4>
                                            <p>
                                                true love is...
                                            </p>
                                        </div>
                                    </div>
                                </div>
                                <NuxtLink to="#" class="load-more">
                                    load More
                                </NuxtLink>
                            </div>
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

<style lang="scss" scoped>

</style>
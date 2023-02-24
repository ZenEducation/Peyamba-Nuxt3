<template>
    <div>
        <section class="product-category">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap ">
                <div class="lg:w-full pr-4 pl-4">
                    <div class="flex flex-wrap ">
                        <div class="lg:w-full pr-4 pl-4">
                            <div class="filter-area">
                                <div class="filter-main">

                                    <ul class="flex flex-wrap list-none pl-0 mb-0 grid-button tab-menu" role="tablist">
                                        <li id="gird-view" class="gird-view">
                                            <NuxtLink class="active" id="nav-gird-tab" data-toggle="tab" to="#nav-gird" role="tab" aria-controls="nav-gird" aria-selected="true">
                                                <i class="fas fa-th"></i>
                                            </NuxtLink>

                                        </li>
                                        <li id="list-view" class="list-view">
                                            <NuxtLink class="" id="nav-list-tab" data-toggle="tab" to="#nav-list" role="tab" aria-controls="nav-list" aria-selected="false">
                                                <i class="fas fa-bars"></i>
                                            </NuxtLink>
                                        </li>
                                    </ul>
                                    <div class="right">
                                        <div class="item">
                                            <span class="opacity-100 block">Show :</span>
                                            <select class="select-bar">
                                                <option value="12">12</option>
                                                <option value="15">15</option>
                                                <option value="18">18</option>
                                                <option value="21">21</option>
                                                <option value="24">24</option>
                                                <option value="27">27</option>
                                                <option value="30">30</option>
                                            </select>
                                        </div>
                                        <div class="item">
                                            <span class="opacity-100 block">Sort By :</span>
                                            <select class="select-bar">
                                                <option value="showing">New</option>
                                                <option value="exclusive">exclusive</option>
                                                <option value="trending">trending</option>
                                                <option value="most-view">most view</option>
                                            </select>
                                        </div>
                                        <div class="serch-icon">
                                            <i class="fas fa-search"></i>
                                        </div>
                                    </div>
                                </div>

                                <div class="search-box">
                                    <input type="text" placeholder="Enter Your Text hear">
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-content" id="nav-tabContent">
                        <div class="tab-pane  opacity-100 block active" id="nav-gird" role="tabpanel" aria-labelledby="nav-gird-tab">
                            <div class="flex flex-wrap ">
                                <div class="xl:w-1/4 lg:w-1/3 md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/02.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/03.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/04.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/05.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/06.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/07.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/08.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/09.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/10.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/11.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/4  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/12.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="tab-pane opacity-0" id="nav-list" role="tabpanel" aria-labelledby="nav-list-tab">
                            <div class="flex flex-wrap ">
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/02.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/03.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/04.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/05.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/06.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/07.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                        </div>
                                    </div>
                                </div>
                                <div class="xl:w-1/2  lg:w-1/3  md:w-1/2 pr-4 pl-4">
                                    <div class="single-product-list-2">
                                        <div class="img">
                                            <img src="@/assets/frontend/images/shoping/ShopPage_01/08.jpg" alt="">
                                            <span class="sale">Sale</span>
                                            <ul class="more-links">
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-sliders-h"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="fas fa-heart"></i>
                                                    </NuxtLink>
                                                </li>
                                                <li>
                                                    <NuxtLink to="#">
                                                        <i class="far fa-eye"></i>
                                                    </NuxtLink>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="content">
                                            <span class="price"> 
                                                $15
                                            </span>
                                            <h4 class="title">
                                                Butterfly Rings
                                            </h4>
                                            <div class="review-area">
                                                <div class="stars">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </div>
                                                <span class="separator">
                                                    |
                                                </span>
                                                <span class="review-content">
                                                    229 review
                                                </span>
                                            </div>
                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
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
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>
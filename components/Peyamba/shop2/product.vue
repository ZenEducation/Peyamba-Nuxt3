<template>
    <div>
        <section class="product-category">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap ">

                <div class="lg:w-1/4 pr-4 pl-4 product-md-grid">


                    <div class="widget-1 widget-range-slider">
                        <div class="widget-1-body">
                            <h6 class="subtitle">Filter by Price</h6>
                            <div class="price-range-slider">
                                <div id="slider"></div>
                                <div class="p-info">
                                    <div class="left">
                                        Price:
                                    </div>
                                    <div class="right">
                                        $0-$1000
                                    </div>
                                </div>
                                <NuxtLink to="#" class="custom-button">Filter</NuxtLink>
                            </div>
                        </div>
                    </div>
                    <div class="widget-1 widget-check">
                        <div class="widget-1-body">
                            <h6 class="subtitle">Gender</h6>
                            <div class="check-area">
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="men"><label for="men">Men (30)</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="women"><label for="women">Women (25)</label>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="widget-1 widget-check">
                        <div class="widget-1-body">
                            <h6 class="subtitle">Categories</h6>
                            <div class="check-area">
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="c1"><label for="c1">Jewelry & Accessories</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="c2"><label for="c2">Rings</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="c3"><label for="c3">Watches</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="c4"><label for="c4">Consumer Electronics</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="c5"><label for="c5">Gift item</label>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="widget-1 widget-check">
                        <div class="widget-1-body">
                            <h6 class="subtitle">Color</h6>
                            <div class="check-area">
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="r1"><label for="r1">Blue (11)</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="r2"><label for="r2">Black (5)</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="r3"><label for="r3">Pink (4)</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="r4"><label for="r4">Multi-Coloured (3)</label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="r5"><label for="r5">Yellow (2)</label>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="widget-1 widget-check rating">
                        <div class="widget-1-body">
                            <h6 class="subtitle">Rating</h6>
                            <div class="check-area">
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="s1"><label for="s1">
                                        <span class="text">
                                            5 star(9)
                                        </span>
                                        <span class="rating">
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                        </span>
                                    </label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="s2"><label for="s2">
                                        <span class="text">
                                            4 star(9)
                                        </span>
                                        <span class="rating">
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="far fa-star"></i>
                                        </span>
                                    </label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="s3"><label for="s3">
                                        <span class="text">
                                            3 star(9)
                                        </span>
                                        <span class="rating">
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="far fa-star"></i>
                                            <i class="far fa-star"></i>
                                        </span>
                                    </label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="s4"><label for="s4">
                                        <span class="text">
                                            2 star(9)
                                        </span>
                                        <span class="rating">
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                            <i class="far fa-star"></i>
                                            <i class="far fa-star"></i>
                                            <i class="far fa-star"></i>
                                        </span>
                                    </label>
                                </div>
                                <div class="mb-4">
                                    <input type="checkbox" name="mode" id="s5"><label for="s5">
                                        <span class="text">
                                            1 star(9)
                                        </span>
                                        <span class="rating">
                                            <i class="fas fa-star"></i>
                                            <i class="far fa-star"></i>
                                            <i class="far fa-star"></i>
                                            <i class="far fa-star"></i>
                                            <i class="far fa-star"></i>
                                        </span>
                                    </label>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:w-3/4 pr-4 pl-4">
                    <div class="flex flex-wrap ">
                        <div class="lg:w-full pr-4 pl-4">
                            <div class="filter-area">
                                <div class="filter-main">

                                    <ul class="flex flex-wrap list-none pl-0 mb-0 grid-button tab-menu" role="tablist">
                                        <li id="gird-view" class="gird-view">
                                            <NuxtLink class="active" id="pills-gird-tab" data-toggle="pill" to="#pills-gird" role="tab" aria-controls="pills-gird" aria-selected="true">
                                                <i class="fas fa-th"></i>
                                            </NuxtLink>

                                        </li>
                                        <li id="list-view" class="list-view">
                                            <NuxtLink class="" id="pills-list-tab" data-toggle="pill" to="#pills-list" role="tab" aria-controls="pills-list" aria-selected="false">
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
                    <div class="tab-content" id="pills-tabContent">
                        <div class="tab-pane  opacity-100 block active" id="pills-gird" role="tabpanel" aria-labelledby="pills-gird-tab">
                            <div class="flex flex-wrap ">
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 pr-4 pl-4 md:w-1/2">
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
                                <div class="lg:w-1/3 md:w-1/2 pr-4 pl-4">
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
                                <div class="lg:w-1/3 md:w-1/2 pr-4 pl-4">
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
                        <div class="tab-pane opacity-0" id="pills-list" role="tabpanel" aria-labelledby="pills-list-tab">
                            <div class="flex flex-wrap ">
                                <div class="lg:w-full pr-4 pl-4">
                                    <div class="spl-wrapper">
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-col">
                                            <div class="single-product-list">
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
                                                    <div class="content-inner">
                                                        <div class="left-content">
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

                                                            <NuxtLink to="#" class="add-wish-btn">
                                                                <i class="fas fa-heart"></i> Add to wish list
                                                            </NuxtLink>
                                                        </div>
                                                        <div class="right-content">
                                                            <NuxtLink class="hover-effect" to="/peyamba/singleshope"><span class="font-16-semibold">Buy Now</span></NuxtLink>
                                                            <NuxtLink to="#" class="more-info">More Info</NuxtLink>
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
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>
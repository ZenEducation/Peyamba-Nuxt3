<template>
    <div>
        <section class="blog-page">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap ">
                <div class="lg:w-2/3 pr-4 pl-4">
                    <div class="single-blog post-details">
                        <div class="img">
                            <img src="@/assets/frontend/images/blog/blog1.png" alt="">
                        </div>
                        <div class="content">
                            <div class="left">
                                <div class="avatar">
                                    <img src="@/assets/frontend/images/blog/author-avarat.png" alt="">
                                </div>
                                <ul class="meta-list">
                                    <li>
                                        <NuxtLink to="#">
                                            <i class="far fa-comments"></i>
                                        </NuxtLink>
                                        <span>30</span>
                                    </li>
                                    <li>
                                        <NuxtLink to="#">
                                            <i class="fas fa-share-alt"></i>
                                        </NuxtLink>
                                        <span>22</span>
                                    </li>
                                </ul>
                            </div>
                            <div class="right">
                                <p class="date">
                                    December 19, 2021
                                </p>
                                <div class="post-header">
                                    <h4 class="m-title">
                                        Cheap Movie Tickets - Bring Your Loved Ones to See New Releases
                                    </h4>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor dunt ut labore et dolore magna aliqua.Quis ipsum suspendisse ultrices gravida. Risus do viverra maecenas accumsan lacus vel facilisis.
                                    </p>
                                    <blockquote>
                                        Modi perferendis ipsa, dolorum eaque accusantium! Velitlibero fugit dolores repellendus consequatur nisi, deserunt aperiam a ea ex hic, iusto atque, quas. Aliquam rerum dolores saepe sunt, assumenda voluptas.
                                    </blockquote>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor dunt ut labore et dolore magna aliqua.Quis ipsum suspendisse ultrices gravida. Risus do viverra maecenas accumsan lacus vel facilisis.
                                    </p>
                                    <h4 class="title">
                                        Bring Your Loved Ones to See New Releases
                                    </h4>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor dunt ut labore et dolore magna aliqua.Quis ipsum suspendisse ultrices gravida. Risus do viverra maecenas accumsan lacus vel facilisis.
                                    </p>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor dunt ut labore et dolore magna aliqua.Quis ipsum suspendisse ultrices gravida. Risus do viverra maecenas accumsan lacus vel facilisis.
                                    </p>
                                </div>
                                <div class="tags-area">
                                    <div class="tags">
                                        <span>
                                            Tags :
                                        </span>
                                        <div class="tags-item">
                                            <NuxtLink to="#"> Tickets </NuxtLink>
                                            <NuxtLink to="#"> Coming Soon </NuxtLink>
                                            <NuxtLink to="#"> Movies </NuxtLink>
                                        </div>
                                    </div>
                                    <ul class="social-icons">
                                        <li>
                                            <NuxtLink to="#">
                                                <i class="fab fa-facebook-f"></i>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="#" class="active">
                                                <i class="fab fa-twitter"></i>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="#">
                                                <i class="fab fa-instagram"></i>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="#">
                                                <i class="fab fa-pinterest"></i>
                                            </NuxtLink>
                                        </li>
                                        <li>
                                            <NuxtLink to="#">
                                                <i class="fab fa-google"></i>
                                            </NuxtLink>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="blog-author">
                        <div class="author-thumb">
                            <NuxtLink to="#">
                                <img src="./@/assets/frontend/images/blog/blog-admin-big.png" alt="blog">
                            </NuxtLink>
                        </div>
                        <div class="author-content">
                            <h5 class="title">
                                <NuxtLink to="#">
                                    Lee Burke
                                </NuxtLink>
                            </h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor dunt ut labore et dolore magna aliqua.Quis ipsum suspendisse .
                            </p>
                        </div>
                    </div>
                    <div class="blog-comment">
                        <h5 class="title">comments</h5>
                        <ul class="comment-area">
                            <li>
                                <div class="blog-thumb">
                                    <NuxtLink to="#">
                                        <img src="@/assets/frontend/images/blog/comment-1.png" alt="blog">
                                    </NuxtLink>
                                </div>
                                <div class="blog-thumb-info">
                                    <span>13 days ago</span>
                                    <h6 class="title"><NuxtLink to="#">carl morgan</NuxtLink></h6>
                                </div>
                                <div class="blog-content">
                                    <p>
                                        Maecenas at velit eu erat egestas vestibulum id ut tellus. Sed et semper mauris. Quisque eu lorem libero. Donec finibus metus tellus, eget rutrum est mattis non.
                                    </p>
                                </div>
                            </li>
                            <li>
                                <div class="blog-thumb">
                                    <NuxtLink to="#">
                                        <img src="@/assets/frontend/images/blog/comment-1.png" alt="blog">
                                    </NuxtLink>
                                </div>
                                <div class="blog-thumb-info">
                                    <span>13 days ago</span>
                                    <h6 class="title"><NuxtLink to="#">john flores</NuxtLink></h6>
                                </div>
                                <div class="blog-content">
                                    <p>
                                        Maecenas at velit eu erat egestas vestibulum id ut tellus. Sed et semper mauris. Quisque eu lorem libero. Donec finibus metus tellus, eget rutrum est mattis non.
                                    </p>
                                </div>
                            </li>
                            <li>
                                <div class="blog-thumb">
                                    <NuxtLink to="#">
                                        <img src="@/assets/frontend/images/blog/comment-1.png" alt="blog">
                                    </NuxtLink>
                                </div>
                                <div class="blog-thumb-info">
                                    <span>13 days ago</span>
                                    <h6 class="title"><NuxtLink to="#">carl morgan</NuxtLink></h6>
                                </div>
                                <div class="blog-content">
                                    <p>
                                        Maecenas at velit eu erat egestas vestibulum id ut tellus. Sed et semper mauris. Quisque eu lorem libero. Donec finibus metus tellus, eget rutrum est mattis non.
                                    </p>
                                </div>
                            </li>
                        </ul>
                        <div class="leave-comment">
                            <h5 class="title">leave comment</h5>
                            <form class="blog-form">
                                <div class="mb-4">
                                    <input type="text" class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" placeholder="Enter Your Full Name" required>
                                </div>
                                <div class="mb-4">
                                    <input type="text" class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" placeholder="Enter Your Email Address" required>
                                </div>
                                <div class="mb-4">
                                    <textarea placeholder="Write A Message" class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" required></textarea>
                                </div>
                                <div class="mb-4">
                                    <button class="custom-button" type="submit">Submit Now</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/3 sm:w-4/5  md:w-2/3 pr-4 pl-4">
                    <div class="widget widget-search">
                        <h5 class="title">search</h5>
                        <form class="search-form">
                            <input type="text" placeholder="Enter your Search Content" required>
                            <button type="submit"><i class="flaticon-loupe"></i>Search</button>
                        </form>
                    </div>
                    <div class="widget widget-categories">
                        <h5 class="title">categories</h5>
                        <ul>
                            <li>
                                <NuxtLink to="#">
                                    <span>Showtimes & Tickets</span><span>50</span>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">
                                    <span>Latest Trailers</span><span>43</span>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">
                                    <span>Coming Soon </span><span>34</span>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">
                                    <span>In Theaters</span><span>63</span>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">
                                    <span>Release Calendar </span><span>11</span>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">
                                    <span>Stars</span><span>30</span>
                                </NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">
                                    <span>Horror Movie </span><span>55</span>
                                </NuxtLink>
                            </li>
                        </ul>
                    </div>
                    <div class="widget widget-post">
                        <h5 class="title">latest post</h5>
                        <div class="slider-nav">
                            <span class="flaticon-angle-pointing-to-left widget-prev"></span>
                            <span class="flaticon-right-arrow-angle widget-next active"></span>
                        </div>
                        <div class="widget-slider owl-carousel owl-theme">
                            <div class="item">
                                <div class="thumb">
                                    <NuxtLink to="#">
                                        <img src="@/assets/frontend/images/blog/resent-post.png" alt="blog">
                                    </NuxtLink>
                                </div>
                                <div class="content">
                                    <h6 class="p-title">
                                        <NuxtLink to="#">How to Start, Plan, and Keep a
                                            Date Night</NuxtLink>
                                    </h6>
                                    <div class="meta-post">
                                        <NuxtLink to="#" class="mr-4"><i class="fas fa-user"></i>Admin</NuxtLink>
                                        <NuxtLink to="#"> <i class="far fa-comments"></i> Comments</NuxtLink>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="thumb">
                                    <NuxtLink to="#">
                                        <img src="@/assets/frontend/images/blog/resent-post.png" alt="blog">
                                    </NuxtLink>
                                </div>
                                <div class="content">
                                    <h6 class="p-title">
                                        <NuxtLink to="#">How to Start, Plan, and Keep a
                                            Date Night</NuxtLink>
                                    </h6>
                                    <div class="meta-post">
                                        <NuxtLink to="#" class="mr-4"><i class="fas fa-user"></i>Admin</NuxtLink>
                                        <NuxtLink to="#"> <i class="far fa-comments"></i> Comments</NuxtLink>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="widget widget-newsletter">
                        <h5 class="title">Newsletter</h5>
                        <form class="search-form">
                            <input type="text" placeholder="Enter your Email Address" required>
                            <button type="submit"><i class="far fa-envelope"></i> Send</button>
                        </form>
                    </div>
                    <div class="widget widget-tags">
                        <h5 class="title">featured tags</h5>
                        <ul>
                            <li>
                                <NuxtLink to="#">creative</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">design</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">skill</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#">template</NuxtLink>
                            </li>
                            <li>
                                <NuxtLink to="#" class="active">landing</NuxtLink>
                            </li>
                        </ul>
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
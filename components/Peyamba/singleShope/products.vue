<template>
    <div>
        <section class="product-details-section">
        <div class="overlay">

            <div class="container mx-auto sm:px-4">
                <div class="flex flex-wrap  mb-90">
                    <div class="lg:w-3/5 pr-4 pl-4">
                        <div class="xzoom-container">
                            <img class="xzoom5" id="xzoom-magnific" src="@/assets/frontend/images/shoping/SingleShop/01.jpg" xoriginal="@/assets/frontend/images/shoping/SingleShop/01.jpg" />
                            <div class="xzoom-thumbs">

                                <div class="all-slider owl-carousel">

                                    <a href="@/assets/frontend/images/shoping/SingleShop/01.jpg">
                                        <img class="xzoom-gallery5" width="80" src="@/assets/frontend/images/shoping/SingleShop/01.jpg" title="The description goes here">
                                    </a>

                                    <a href="@/assets/frontend/images/shoping/SingleShop/02.jpg">
                                        <img class="xzoom-gallery5" width="80" src="@/assets/frontend/images/shoping/SingleShop/02.jpg" title="The description goes here">
                                    </a>

                                    <a href="@/assets/frontend/images/shoping/SingleShop/03.jpg">
                                        <img class="xzoom-gallery5" width="80" src="@/assets/frontend/images/shoping/SingleShop/03.jpg" title="The description goes here">
                                    </a>
                                    <a href="@/assets/frontend/images/shoping/SingleShop/04.jpg">
                                        <img class="xzoom-gallery5" width="80" src="@/assets/frontend/images/shoping/SingleShop/04.jpg" title="The description goes here">
                                    </a>

                                </div>

                            </div>
                        </div>






                    </div>
                    <div class="lg:w-2/5 pr-4 pl-4">
                        <div class="right-area">
                            <div class="product-info">
                                <ul>
                                    <li class="product-stock">
                                        <div class="stock-box">
                                            <span class="value-title">Availability:</span>
                                            <span class="value-content">In Stock</span>
                                        </div>
                                        <div class="stock-icon">
                                            <a href="#">
                                                <i class="fas fa-heart"></i>
                                            </a>
                                        </div>
                                    </li>
                                    <li class="product-title-area">
                                        <h1 class="product-title">Mirrored Swim Goggle</h1>
                                    </li>
                                    <li>
                                        <div class="review-block">
                                            <p class="star-review">
                                                <a href="#" class="star">
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                    <i class="fas fa-star"></i>
                                                </a>
                                                <a href="#" class="reviews"> <span>129</span> review </a>
                                            </p>
                                        </div>
                                    </li>
                                </ul>


                                <div class="product-price">
                                    <p class="price">$<span id="sizeprice">15.00</span></p>
                                </div>

                                <ul class="offers">
                                    <li>
                                        <p>Order 2, get 15% off</p>
                                    </li>
                                    <li>
                                        <p>Order 3, get 20% off</p>
                                    </li>
                                </ul>

                                <div class="product-color">
                                    <p class="title">Color:</p>
                                    <ul class="color-list">
                                        <li>
                                            <span class="box">Red</span>
                                        </li>
                                    </ul>
                                </div>

                                <div class="item-list">
                                    <ul>
                                        <li>
                                            <a href="#"><img src="@/assets/frontend/images/shoping/c1.jpg" alt="image"></a>
                                        </li>
                                        <li>
                                            <a href="#"><img src="@/assets/frontend/images/shoping/c2.jpg" alt="image"></a>
                                        </li>
                                        <li>
                                            <a href="#"><img src="@/assets/frontend/images/shoping/c3.jpg" alt="image"></a>
                                        </li>
                                        <li>
                                            <a href="#"><img src="@/assets/frontend/images/shoping/c4.jpg" alt="image"></a>
                                        </li>
                                    </ul>
                                </div>

                                <div class="shiping-area">
                                    <h4 class="title">Shipping:</h4>
                                    <div class="content">
                                        <div class="s-drop">
                                            <select class="select-bar">
                                                <option value="">Processing time:1-3 business days</option>
                                                <option value="1">Processing time:1-3 business days</option>
                                                <option value="2">Processing time:1-3 business days</option>
                                            </select>
                                        </div>
                                        <div class="s-drop">
                                            <select class="select-bar">
                                                <option value="">Free shipping via Standard Shipping</option>
                                                <option value="1">Free shipping via Standard Shipping</option>
                                                <option value="2">Free shipping via Standard Shipping</option>
                                            </select>
                                        </div>
                                        <div class="s-drop">
                                            <select class="select-bar">
                                                <option value="">Shipping time:7-35 business days</option>
                                                <option value="1">Shipping time:7-35 business days</option>
                                                <option value="2">Shipping time:7-35 business days</option>
                                            </select>
                                        </div>
                                    </div>
                                </div>
                                <div class="input-counter flex">
                                    <div class="qtySelector text-center">
                                        <i class="fas fa-minus decreaseQty"></i>
                                        <input type="text" class="qtyValue" value="1" />
                                        <i class="fas fa-plus increaseQty"></i>
                                    </div>
                                    <button class="add-cart-btn custom-button"> <i class="icofont-shopping-cart"></i>
                                        Add to Cart</button>
                                </div>

                                <div class="product-single-share">
                                    <label>Share link:</label>
                                    <ul class="footer-brand">
                                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                                        <li><a href="#" class="active"><i class="fab fa-twitter"></i></a></li>
                                        <li><a href="#"><i class="fab fa-pinterest"></i></a></li>
                                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                                        <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                                    </ul>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
                <div class="flex flex-wrap ">
                    <div class="lg:w-full pr-4 pl-4">
                        <ul class="flex flex-wrap list-none pl-0 mb-0 border border-t-0 border-r-0 border-l-0 border-b-1 border-gray-200" id="myTab" role="tablist">
                            <li class="">
                                <a class="inline-block py-2 px-4 no-underline" data-toggle="tab" href="#frist">Product Information</a>
                            </li>
                            <li class="">
                                <a class="inline-block py-2 px-4 no-underline" data-toggle="tab" href="#second">Product Detail</a>
                            </li>
                            <li class="">
                                <a class="inline-block py-2 px-4 no-underline" data-toggle="tab" href="#third">Product feature</a>
                            </li>
                            <li class="">
                                <a class="inline-block py-2 px-4 no-underline" data-toggle="tab" href="#fourth">Delivery & Returns</a>
                            </li>
                            <li class="">
                                <a class="inline-block py-2 px-4 no-underline active" data-toggle="tab" href="#fifth">Reviews</a>
                            </li>
                        </ul>
                        <div class="tab-content" id="myTabContent">
                            <div class="tab-pane opacity-0" id="frist">
                                <div class="tab-content-wrapper">
                                    <p class="font-18-normal mb-30">
                                        The MPS XCEED Goggles have a patented curved lens for expanded field of vision allows the swimmer to sight walls and the competition without altering head position. Engineered with Exo-Core technology, which combines two materials for maximum performance.
                                        Compressed Micro-Gasket made of ultra-soft Softeril and provides a leak resistant seal and a low-profile design. Semi-rigid exoskeleton maximizes the structural strength and stability of the goggle. Hydrodynamic,
                                        low-profile head buckle for quick adjustments. High-quality, low-profile silicone strap with textured grip effect. Clear vision is assured with anti-fog treated polycarbonate lenses. Goggles have ergonomic, easy
                                        to replace, interchangeable nose bridge for a customizable, comfortable fit. Designed and manufactured in Italy and are FINA approved.
                                    </p>
                                    <ul class="font-18-normal">
                                        <li>
                                            <i class="icofont-caret-right"></i> Asymmetric and anatomically designed lens
                                        </li>
                                        <li>
                                            <i class="icofont-caret-right"></i> Wider field of vision
                                        </li>
                                        <li>
                                            <i class="icofont-caret-right"></i> High performing hydrodynamic shape
                                        </li>
                                        <li>
                                            <i class="icofont-caret-right"></i> Low profile side loops and micro head buckles
                                        </li>
                                        <li>
                                            <i class="icofont-caret-right"></i> Includes 4 nosepiece options for custom fit
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <div class="tab-pane opacity-0" id="second">
                                <div class="tab-content-wrapper-second">
                                    <h4 class="title mb-30">Specification:</h4>
                                    <ul class="top-content mb-30">
                                        <li>
                                            Lens Material:
                                            <span>PC</span>
                                        </li>
                                        <li>
                                            Head Band:
                                            <span>Silica gel</span>
                                        </li>
                                        <li>
                                            Fit People:
                                            <span>Adult</span>
                                        </li>
                                        <li>
                                            Gender:
                                            <span>Unisex</span>
                                        </li>
                                        <li>
                                            Net Weight:
                                            <span>145g</span>
                                        </li>
                                        <li>
                                            Size:
                                            <span>156.5x39.1cm</span>
                                        </li>
                                        <li>
                                            Function:
                                            <span>Waterproof, Anti-fog, UV-proof</span>
                                        </li>
                                    </ul>


                                </div>
                            </div>
                            <div class="tab-pane opacity-0" id="third">
                                <div class="tab-content-wrapper-third">

                                    <h4 class="title mb-30">FINA Approved:</h4>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam ducimus cum sunt quas, exercitationem et sit a quos culpa ratione, atque nobis fugiat accusamus dolores perspiciatis facilis blanditiis optio suscipit.
                                    </p>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam ducimus cum sunt quas, exercitationem et sit a quos culpa ratione, atque nobis fugiat accusamus dolores perspiciatis facilis blanditiis optio suscipit.Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Totam ducimus cum sunt quas, exercitationem et sit a quos culpa ratione, atque nobis fugiat accusamus dolores perspiciatis facilis blanditiis optio suscipit.
                                    </p>
                                </div>
                            </div>
                            <div class="tab-pane opacity-0" id="fourth">
                                <div class="tab-content-wrapper-fourth">

                                    <h4 class="title mb-30">Delivery & Returns:</h4>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam ducimus cum sunt quas, exercitationem et sit a quos culpa ratione, atque nobis fugiat accusamus dolores perspiciatis facilis blanditiis optio suscipit.
                                    </p>
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam ducimus cum sunt quas, exercitationem et sit a quos culpa ratione, atque nobis fugiat accusamus dolores perspiciatis facilis blanditiis optio suscipit.Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Totam ducimus cum sunt quas, exercitationem et sit a quos culpa ratione, atque nobis fugiat accusamus dolores perspiciatis facilis blanditiis optio suscipit.
                                    </p>
                                </div>
                            </div>
                            <div class="tab-pane  opacity-100 block active fifth" id="fifth">
                                <div class="tab-content-wrapper-fifth">
                                    <div class="top-content-fifth mb-30">
                                        <h4 class="title mb-30">Reviews</h4>
                                        <div class=" flex-wrap  flex justify-around">
                                            <div class="lg:w-1/3 pr-4 pl-4">
                                                <div class="averages-review text-center">
                                                    <div class="rating"><span>5.0</span>/5</div>
                                                    <div class="review-block">
                                                        <p class="star-review">
                                                            <a href="#" class="star">
                                                                <i class="fas fa-star"></i>
                                                                <i class="fas fa-star"></i>
                                                                <i class="fas fa-star"></i>
                                                                <i class="fas fa-star"></i>
                                                                <i class="fas fa-star"></i>
                                                            </a>
                                                            <a href="#" class="reviews"> <span>129</span> review </a>
                                                        </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="lg:w-1/2 pr-4 pl-4">
                                                <ul class="rating-list">
                                                    <li class="rating-breakdown">

                                                        <div class="rating-point">
                                                            <span>5 Stars</span>
                                                        </div>

                                                        <div class="progress">
                                                            <div class="progress-bar full" role="progressbar"></div>
                                                        </div>
                                                        <div class="review-count">
                                                            <a href="#">(129)</a>
                                                        </div>

                                                    </li>
                                                </ul>
                                                <ul class="rating-list">
                                                    <li class="rating-breakdown">

                                                        <div class="rating-point">
                                                            <span>4 Stars</span>
                                                        </div>

                                                        <div class="progress">
                                                            <div class="progress-bar eighty" role="progressbar"></div>
                                                        </div>
                                                        <div class="review-count">
                                                            <a href="#">(12)</a>
                                                        </div>

                                                    </li>
                                                </ul>
                                                <ul class="rating-list">
                                                    <li class="rating-breakdown">

                                                        <div class="rating-point">
                                                            <span>3 Stars</span>
                                                        </div>

                                                        <div class="progress">
                                                            <div class="progress-bar" role="progressbar"></div>
                                                        </div>
                                                        <div class="review-count">
                                                            <a href="#">(0)</a>
                                                        </div>

                                                    </li>
                                                </ul>
                                                <ul class="rating-list">
                                                    <li class="rating-breakdown">

                                                        <div class="rating-point">
                                                            <span>2 Stars</span>
                                                        </div>

                                                        <div class="progress">
                                                            <div class="progress-bar" role="progressbar"></div>
                                                        </div>
                                                        <div class="review-count">
                                                            <a href="#">(0)</a>
                                                        </div>

                                                    </li>
                                                </ul>
                                                <ul class="rating-list">
                                                    <li class="rating-breakdown">

                                                        <div class="rating-point">
                                                            <span>1 Star</span>
                                                        </div>

                                                        <div class="progress">
                                                            <div class="progress-bar" role="progressbar"></div>
                                                        </div>
                                                        <div class="review-count">
                                                            <a href="#">(0)</a>
                                                        </div>

                                                    </li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="single-comment mb-30">
                                        <div class="flex flex-wrap ">
                                            <div class="lg:w-full pr-4 pl-4">
                                                <div class="comment-single">
                                                    <div class="avatar">
                                                        <img src="@/assets/frontend/images/shoping/reviewr1.png" class="max-w-full h-auto" alt="">
                                                    </div>
                                                    <div class="comnt-text">
                                                        <div class="reply-icon">
                                                            <a href="#">Reply <i class="fas fa-reply-all"></i></a>
                                                        </div>
                                                        <div class="comnt-info">
                                                            <h5>Angel Smith</h5>
                                                            <div class="review-block">
                                                                <p class="star-review">
                                                                    <a href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </a>
                                                                </p>
                                                            </div>

                                                            <p class="date-area">November 20, 2018 at 8:31 pm</p>
                                                        </div>
                                                        <p class="">Maecenas at turpis ut lacus posuere dapibus. Fusce et sollicitudin libero, id vehicula sem. Morbi pharetra nisl eget neque commodo facilisis. Nunc malesuada dolor vitae feugiat fermentum.</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="single-comment mb-30">
                                        <div class="flex flex-wrap ">
                                            <div class="lg:w-full pr-4 pl-4">
                                                <div class="comment-single">
                                                    <div class="avatar">
                                                        <img src="@/assets/frontend/images/shoping/reviewr2.png" class="max-w-full h-auto" alt="">
                                                    </div>
                                                    <div class="comnt-text">
                                                        <div class="reply-icon">
                                                            <a href="#">Reply <i class="fas fa-reply-all"></i></a>
                                                        </div>
                                                        <div class="comnt-info">
                                                            <h5>Pablo Hicks</h5>
                                                            <div class="review-block">
                                                                <p class="star-review">
                                                                    <a href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </a>
                                                                </p>
                                                            </div>

                                                            <p class="date-area">November 20, 2018 at 8:31 pm</p>
                                                        </div>
                                                        <p class="font-16-regular">Maecenas at turpis ut lacus posuere dapibus. Fusce et sollicitudin libero, id vehicula sem. Morbi pharetra nisl eget neque commodo facilisis. Nunc malesuada dolor vitae feugiat fermentum.</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="single-comment mb-30">
                                        <div class="flex flex-wrap ">
                                            <div class="lg:w-full pr-4 pl-4">
                                                <div class="comment-single">
                                                    <div class="avatar">
                                                        <img src="@/assets/frontend/images/shoping/reviewr3.png" class="max-w-full h-auto" alt="">
                                                    </div>
                                                    <div class="comnt-text">
                                                        <div class="reply-icon">
                                                            <a href="#">Reply <i class="fas fa-reply-all"></i></a>
                                                        </div>
                                                        <div class="comnt-info">
                                                            <h5>Noel Webster</h5>
                                                            <div class="review-block">
                                                                <p class="star-review">
                                                                    <a href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </a>
                                                                </p>
                                                            </div>

                                                            <p class="date-area">November 20, 2018 at 8:31 pm</p>
                                                        </div>
                                                        <p class="font-16-regular">Maecenas at turpis ut lacus posuere dapibus. Fusce et sollicitudin libero, id vehicula sem. Morbi pharetra nisl eget neque commodo facilisis. Nunc malesuada dolor vitae feugiat fermentum.</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="flex flex-wrap ">
                                        <div class="lg:w-full pr-4 pl-4">
                                            <div class="pagination-area text-center">
                                                <a href="#"><i class="fas fa-angle-double-left"></i><span></span></a>
                                                <a href="#">1</a>
                                                <a href="#">2</a>
                                                <a href="#" class="active">3</a>
                                                <a href="#">4</a>
                                                <a href="#">5</a>
                                                <a href="#"><i class="fas fa-angle-double-right"></i></a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="flex flex-wrap ">
                                        <div class="lg:w-3/4 pr-4 pl-4">
                                            <div class="comment-form">
                                                <h3 class="mb-60">Add a Review</h3>

                                                <div class="star-area flex justify-between">
                                                    <h5>Your Rating:</h5>
                                                    <ul class="star-list">
                                                        <li>
                                                            <div class="review-block">
                                                                <div class="star-review">
                                                                    <div href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </li>
                                                        <li>
                                                            <div class="review-block">
                                                                <div class="star-review">
                                                                    <div class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </li>
                                                        <li>
                                                            <div class="review-block">
                                                                <div class="star-review">
                                                                    <div href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </li>
                                                        <li>
                                                            <div class="review-block">
                                                                <div class="star-review">
                                                                    <div href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </li>
                                                        <li>
                                                            <div class="review-block">
                                                                <div class="star-review">
                                                                    <div href="#" class="star">
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                        <i class="fas fa-star"></i>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </li>
                                                    </ul>
                                                </div>

                                                <form action="#" method="post">
                                                    <div class="mb-4">
                                                        <input type="text" class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" placeholder="Name">
                                                    </div>
                                                    <div class="mb-4">
                                                        <input type="email" class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" placeholder="Email Address *">
                                                    </div>
                                                    <div class="mb-4">
                                                        <input type="text" class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" placeholder="Subject">
                                                    </div>
                                                    <div class="mb-4 mb-30">
                                                        <textarea class="block appearance-none w-full py-1 px-2 mb-1 text-base leading-normal bg-white text-gray-800 border border-gray-200 rounded" rows="10" placeholder="Your Message"></textarea>
                                                    </div>
                                                    <button class="custom-button" type="submit">POST COMMENT</button>
                                                </form>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="related-product-section">
                    <div class="lg:w-full pr-4 pl-4">
                        <div class="flex flex-wrap  justify-center">
                            <div class="lg:w-1/2 pr-4 pl-4">
                                <div class="content">
                                    <div class="section-header">
                                        <h6 class="sub-title">
                                            Hot Products
                                        </h6>
                                        <h2 class="title extra-padding">
                                            Related To This Item
                                        </h2>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="flex flex-wrap ">
                            <div class="lg:w-full pr-4 pl-4">
                                <div class="related-product-slider owl-carousel">
                                    <div class="slider-item">
                                        <div class="single-product">
                                            <div class="img">
                                                <img src="@/assets/frontend/images/shoping/ShopPage_01/01.jpg" alt="">
                                                <span class="sale">Sale</span>
                                                <ul class="more-links">
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-sliders-h"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-heart"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="far fa-eye"></i>
                                                        </a>
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
                                                <a class="hover-effect" href="#"><span class="font-16-semibold">Buy
                                                        Now</span></a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="slider-item">
                                        <div class="single-product">
                                            <div class="img">
                                                <img src="@/assets/frontend/images/shoping/ShopPage_01/02.jpg" alt="">
                                                <span class="sale">Sale</span>
                                                <ul class="more-links">
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-sliders-h"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-heart"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="far fa-eye"></i>
                                                        </a>
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
                                                <a class="hover-effect" href="#"><span class="font-16-semibold">Buy
                                                        Now</span></a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="slider-item">
                                        <div class="single-product">
                                            <div class="img">
                                                <img src="@/assets/frontend/images/shoping/ShopPage_01/03.jpg" alt="">
                                                <span class="sale">Sale</span>
                                                <ul class="more-links">
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-sliders-h"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-heart"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="far fa-eye"></i>
                                                        </a>
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
                                                <a class="hover-effect" href="#"><span class="font-16-semibold">Buy
                                                        Now</span></a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="slider-item">
                                        <div class="single-product">
                                            <div class="img">
                                                <img src="@/assets/frontend/images/shoping/ShopPage_01/04.jpg" alt="">
                                                <span class="sale">Sale</span>
                                                <ul class="more-links">
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-sliders-h"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-heart"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="far fa-eye"></i>
                                                        </a>
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
                                                <a class="hover-effect" href="#"><span class="font-16-semibold">Buy
                                                        Now</span></a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="slider-item">
                                        <div class="single-product">
                                            <div class="img">
                                                <img src="@/assets/frontend/images/shoping/ShopPage_01/05.jpg" alt="">
                                                <span class="sale">Sale</span>
                                                <ul class="more-links">
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-sliders-h"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="fas fa-heart"></i>
                                                        </a>
                                                    </li>
                                                    <li>
                                                        <a href="#">
                                                            <i class="far fa-eye"></i>
                                                        </a>
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
                                                <a class="hover-effect" href="#"><span class="font-16-semibold">Buy
                                                        Now</span></a>
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
    </section>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>
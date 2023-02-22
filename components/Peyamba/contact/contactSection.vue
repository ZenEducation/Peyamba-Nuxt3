<template>
    <div>
        <section class="contact-section">
        <img class="img-left" src="@/assets/frontend/images/contact/img-left.png" alt="">
        <img class="img-right" src="@/assets/frontend/images/contact/img-right.png" alt="">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap  justify-center">
                <div class="lg:w-1/2 pr-4 pl-4">
                    <div class="content">
                        <div class="section-header">
                            <h6 class="sub-title">
                                Contact Us
                            </h6>
                            <h2 class="title">
                                Get in Touch
                            </h2>
                            <p class="text">
                                We'd love to hear from you! Let us know how we can help.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-wrap ">
                <div class="lg:w-3/5 pr-4 pl-4">
                    <div class="contact-form-wrapper">
                        <div class="single-input">
                            <i class="far fa-user"></i>
                            <input type="text" placeholder="Full Name">
                        </div>
                        <div class="single-input">
                            <i class="far fa-envelope"></i>
                            <input type="text" placeholder="Enter Your Email ID">
                        </div>
                        <div class="single-input">
                            <i class="far fa-comments"></i>
                            <textarea placeholder="Type Your Text"></textarea>
                        </div>
                        <NuxtLink to="#" class="custom-button">Submit</NuxtLink>
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
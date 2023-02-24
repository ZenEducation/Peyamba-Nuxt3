<template>
    <div>
        <section class="banner-section">
        <img class="img1 wow fadeInLeft" src="@/assets/frontend/images/banner/aimg1.png" alt="">
        <img class="img2 wow fadeInRight" src="@/assets/frontend/images/banner/aimg2.png" alt="">
        <div class="container mx-auto sm:px-4">
            <div class="flex flex-wrap ">
                <div class="xl:w-1/3 lg:w-2/5 pr-4 pl-4">
                    <h1 class="main-title wow fadeInLeft">
                        Find Love Your Life
                    </h1>
                    <div class="join-now-box wow fadeInUp">
                        <div class="single-option">
                            <p class="title">
                                I am a :
                            </p>
                            <div class="option">
                                <div class="s-input mr-3">
                                    <input type="radio" name="gender" id="male"><label for="male">Male</label>
                                </div>
                                <div class="s-input">
                                    <input type="radio" name="gender" id="female"><label for="female">Female</label>
                                </div>
                            </div>
                        </div>
                        <div class="single-option gender">
                            <p class="title">
                                Seeking a :
                            </p>
                            <div class="option">
                                <div class="s-input mr-4">
                                    <input type="radio" name="seeking" id="males"><label for="males">Man</label>
                                </div>
                                <div class="s-input">
                                    <input type="radio" name="seeking" id="females"><label for="females">Woman</label>
                                </div>
                            </div>
                        </div>
                        <div class="single-option age">
                            <p class="title">
                                Ages :
                            </p>
                            <div class="option">
                                <div class="s-input mr-3">
                                    <select class="select-bar">
                                        <option value="">18</option>
                                        <option value="">20</option>
                                        <option value="">24</option>
                                    </select>
                                </div>
                                <div class="separator">
                                    -
                                </div>
                                <div class="s-input ml-3">
                                    <select class="select-bar">
                                        <option value="">30</option>
                                        <option value="">35</option>
                                        <option value="">40</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                        <div class="single-option last">
                            <p class="title">
                                Country :
                            </p>
                            <div class="option">
                                <div class="s-input mr-3">
                                    <select class="select-bar">
                                        <option>Select Country</option>
                                        <option value="">India</option>
                                        <option value="">Japan</option>
                                        <option value="">England</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                        <div class="joun-button">
                            <button class="custom-button">Join Now!</button>
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

<style scoped>

</style>
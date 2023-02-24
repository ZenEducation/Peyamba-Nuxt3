<template>
    <div>
        <section class="log-reg">
        <div class="top-menu-area">
            <div class="container">
                <div class="row">
                    <div class="col-lg-5">
                        <NuxtLink to="/peyamba" class="backto-home"><i class="fas fa-chevron-left"></i> Back to peyamba</NuxtLink>
                    </div>
                    <div class="col-lg-7 ">
                        <div class="logo">
                            <img src="@/assets/frontend/images/logo2.png" alt="logo">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row justify-content-end">
                <div class="image">
                </div>
                <div class="col-lg-7">
                    <div class="log-reg-inner">
                        <div class="section-header">
                            <h2 class="title">
                                Welcome to PEYAMBA
                            </h2>
                            <p>
                                Let's create your profile! Just fill in the fields below, and we’ll get a new account.
                            </p>
                        </div>
                        <div class="main-content">
                            <form action="#">
                                <h4 class="content-title">Acount Details</h4>
                                <div class="form-group">
                                    <label for="">Username*</label>
                                    <input type="text" class="my-form-control" placeholder="Enter Your Usewrname">
                                </div>
                                <div class="form-group">
                                    <label for="">Email Address*</label>
                                    <input type="email" class="my-form-control" placeholder="Enter Your Email">
                                </div>
                                <div class="form-group">
                                    <label for="">Password*</label>
                                    <input type="text" class="my-form-control" placeholder="Enter Your Password">
                                </div>
                                <div class="form-group">
                                    <label for="">Confirm Password*</label>
                                    <input type="text" class="my-form-control" placeholder="Enter Your Password">
                                </div>
                                <h4 class="content-title mt-5">Profile Details</h4>
                                <div class="form-group">
                                    <label for="">Name*</label>
                                    <input type="text" class="my-form-control" placeholder="Enter Your Full Name">
                                </div>
                                <div class="form-group">
                                    <label for="">Birthday*</label>
                                    <input type="date" class="my-form-control">
                                </div>
                                <div class="form-group">
                                    <label for="">I am a*</label>
                                    <div class="option">
                                        <div class="s-input mr-3">
                                            <input type="radio" name="gender1" id="males1"><label for="males1">Man</label>
                                        </div>
                                        <div class="s-input">
                                            <input type="radio" name="gender1" id="females1"><label for="females1">Woman</label>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <label for="">Looking for a*</label>
                                    <div class="option">
                                        <div class="s-input mr-3">
                                            <input type="radio" name="gender2" id="males"><label for="males">Man</label>
                                        </div>
                                        <div class="s-input">
                                            <input type="radio" name="gender2" id="females"><label for="females">Woman</label>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <label for="">Marial status*</label>
                                    <div class="option">
                                        <div class="s-input nice-select-wraper">
                                            <select class="select-bar">
                        <option value="">Single</option>
                        <option value="">Marid</option>
                        <option value="">Marid</option>
                        <option value="">Marid</option>
                      </select>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <label for="">City*</label>
                                    <input type="text" class="my-form-control" placeholder="Enter Your City">
                                </div>
                                <button class="custom-button" data-toggle="modal" data-target="#email-confirm">Create Your
                  Profile</button>
                            </form>
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
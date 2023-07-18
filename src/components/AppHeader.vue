<template>
  <header class="header-area" id="home">
    <div class="container-xl">
        <div class="row align-items-center">
            <div class="col-lg-2 col-md-6 col-sm-6 col-5">
                <!-- Logo  -->
                <div class="logo">
                    <a href="#"><img src="../assets/image/logo.png" alt="logo"></a> 
                </div>
            </div>
            <div class="col-lg-7 col-md-6 menu-items">
                <!-- Menu -->
                <nav class="header-menu">
                    <ul class="primary-menu d-flex justify-content-center">
                        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#feature">Feature</a></li>
                        <li class="nav-item"><a class="nav-link" href="#price">Price</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </nav>
                <a class="small-device-show" href="#"><img src="../assets/image/logo.png" alt="logo"></a>
                <span class="crose-icon"><i class="fa-solid fa-xmark"></i></span>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-6 col-7">
                <!-- Button Area -->
                <div class="header-btn">
                    <a class="login-btn" href="#">Login</a>
                    <a class="signUp-btn" href="#" data-bs-toggle="modal" data-bs-target="#staticBackdrop">Register</a>
                    <span class="hambargar-bar"><i class="fa-solid fa-bars"></i></span>
                </div>
            </div>
        </div>
    </div>
  </header> 
</template>

<script setup>
</script>

<style scoped>
/* Add any custom styling for the header here */
</style>

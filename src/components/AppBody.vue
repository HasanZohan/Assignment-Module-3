<template>
   <!-- Register Form Modal Start -->
   <div class="register-form-modal">
        <!-- Modal -->
        <div class="modal fade" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
            <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <h1 class="modal-title fs-5 text-center" id="staticBackdropLabel">School Register Form</h1>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <form action="#" method="POST">
                        <div class="row">
                            <div class="col-lg-6">
                                <div class="reg-modal-form">
                                    <h4>SCHOOL INFO</h4>
                                    <div class="reg-form-group">
                                        <div class="single-form">
                                            <label for="name">School Name</label>
                                            <input id="name" name="#" type="text" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="adress">School Address</label>
                                            <input id="adress" name="#" type="text" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="email">School Email</label>
                                            <input id="email" name="#" type="email" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="phone">School Phone</label>
                                            <input id="phone" name="#" type="number" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="message">School info</label>
                                           <textarea name="#" id="message" class="form-control"></textarea>
                                        </div>
                                    </div>
                                </div> 
                            </div>
                            <div class="col-lg-6">
                                <div class="reg-modal-form">
                                    <h4>ADMIN INFO</h4>
                                    <div class="reg-form-group">
                                        <div class="single-form">
                                            <label for="name1">Admin Name</label>
                                            <input id="name1" name="#" type="text" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="gender">Gender</label>
                                            <select class="form-select" id="gender">
                                                <option selected>Select a gender</option>
                                                <option value="Male">Male</option>
                                                <option value="Female">Female</option>
                                              </select>
                                        </div>
                                        <div class="single-form">
                                            <label for="blood">Blood group</label>
                                            <select class="form-select">
                                                <option selected>Select a blood group</option>
                                                <option value="A+">A+</option>
                                                <option value="B+">B+</option>
                                                <option value="A-">A-</option>
                                                <option value="B-">B-</option>
                                              </select>
                                        </div>
                                        <div class="single-form">
                                            <label for="Address1">Admin Address</label>
                                            <input id="Address1" name="#" type="text" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="Number">Admin Phone Number</label>
                                            <input id="Number" name="#" type="number" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="Photo">Photo</label>
                                            <input class="form-control" type="file" id="photo" name="photo" >
                                        </div>
                                        <div class="single-form">
                                            <label for="email1">Admin Email</label>
                                            <input id="email1" name="#" type="email" class="form-control">
                                        </div>
                                        <div class="single-form">
                                            <label for="password">Admin Password</label>
                                            <input id="password" name="#" type="password" class="form-control">
                                        </div>
                                    </div>
                                </div> 
                                <button class="m-submit-btn" type="submit">Submit</button>
                            </div>
                        </div>
                    </form>
                </div>
             </div>
            </div>
        </div>
     </div>
 <!-- Register Form Modal End -->
<!--  Bannar Area Start  -->
<section class="bannar-area">
    <!-- Safe -->
    <span class="safe-top"><img src="../assets/image/safe-2.png" alt="img"></span>
    <span class="safe-left"><img src="../assets/image/safe-1.png" alt="img"></span>
    <div class="container-xl">
        <div class="row">
            <div class="col-lg-6">
                <!-- Bannar Content -->
                <div class="bannar-content">
                    <h4>Ekattor 8</h4>
                    <h2>Deep Learning Through Deep Connections</h2>
                    <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected.</p>
                    <div class="ekatoor-user">
                        <div class="single-user">
                            <h3>100+</h3>
                            <span>Features</span>
                        </div>
                        <div class="single-user">
                            <h3>07</h3>
                            <span>User Account</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="bananr-right-img">
                    <img src="../assets/image/bannar-image.png" alt="image">
                </div>
            </div>
        </div>
    </div>
</section>
<!--  Bannar Area End   -->
<!--  Service Area Start  -->
<section class="service-area section-padding" id="feature">
    <div class="container">
        <!-- Title  -->
        <div class="title-area">
            <h1>Our Features</h1>
            <h3>Features</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look</p>
        </div>
        <div class="row mt-5 pt-3">
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-1.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Students Admission</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-2.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Daily Attendance</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12 mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-3.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Class List</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12 mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-4.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Subjects</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-5.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Event Calender</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-6.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Routine</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-7.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Student Information</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-8.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Syllabus</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-9.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Fees Management</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-10.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>ID Card Generator</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-11.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Online Payment Gateway</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-12.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Invoice Generator</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row hide-service">
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-1.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Students Admission</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-2.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Daily Attendance</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12 mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-3.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Class List</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12 mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-4.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Subjects</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-5.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Event Calender</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-12  mb-60">
                <div class="service-items">
                    <div class="service-icon">
                        <img src="../assets/image/feature/icon-6.png" alt="icon-img">
                    </div>
                    <div class="service-text">
                        <h3>Routine</h3>
                        <p>Lorem Ipsum is simply dummy text of the printe typesetting industry. Lorem Ipsum has</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="see-all-btn">
            <a class="see-btn">See all <i class="fa-solid fa-right-long"></i></a>
        </div>
    </div>
</section>
<!--  Feature Area End   -->
<!--  Pricing Area Start   -->
<section class="pricing-area section-padding" id="price">
    <div class="container-xl">
        <!-- Title  -->
        <div class="title-area">
            <h1>Price</h1>
            <h3>Price</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look</p>
        </div>
        <div class="row">
            <div class="col-lg-3 col-md-6 col-sm-6 mb-3">
                <div class="pricing-table">
                    <span class="trail-price">Trail</span>
                    <h4>$00<span class="small-text">/mon</span></h4>
                    <ul class="pricing-item">
                        <li class="color-ff">25 Analytics Campaigns</li>
                        <li>Free Optimization</li>
                        <li>30 Social Media Reviews</li>
                        <li>2 Free Optimization</li>
                        <li class="color-ff">24/7 Support</li>
                    </ul>
                    <a href="#" class="subscribe-btn">Subscribe</a>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-6 mb-3 ">
                <div class="pricing-table">
                    <span class="trail-price">Basic</span>
                    <h4>$175<span class="small-text">/mon</span></h4>
                    <ul class="pricing-item">
                        <li class="color-ff">25 Analytics Campaigns</li>
                        <li class="color-ff">Free Optimization</li>
                        <li>30 Social Media Reviews</li>
                        <li>2 Free Optimization</li>
                        <li class="color-ff">24/7 Support</li>
                    </ul>
                    <a href="#" class="subscribe-btn">Subscribe</a>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-6 mb-3">
                <div class="pricing-table">
                    <span class="trail-price">Premium</span>
                    <h4>$299<span class="small-text">/mon</span></h4>
                    <ul class="pricing-item">
                        <li class="color-ff">25 Analytics Campaigns</li>
                        <li class="color-ff">Free Optimization</li>
                        <li class="color-ff">30 Social Media Reviews</li>
                        <li>2 Free Optimization</li>
                        <li class="color-ff">24/7 Support</li>
                    </ul>
                    <a href="#" class="subscribe-btn">Subscribe</a>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-6  mb-3">
                <div class="pricing-table">
                    <span class="trail-price">Special</span>
                    <h4>$760<span class="small-text">/yea</span></h4>
                    <ul class="pricing-item">
                        <li class="color-ff">25 Analytics Campaigns</li>
                        <li class="color-ff">Free Optimization</li>
                        <li class="color-ff">30 Social Media Reviews</li>
                        <li class="color-ff">2 Free Optimization</li>
                        <li class="color-ff">24/7 Support</li>
                    </ul>
                    <a href="#" class="subscribe-btn">Subscribe</a>
                </div>
            </div>
        </div>
    </div>
</section>
<!--  Pricing Area End   -->
<!--  Faq  Area Start   -->
<section class="faq-area">
    <div class="container-xl">
         <!-- Title  -->
         <div class="title-area">
            <h1>Have Any Question</h1>
            <h3>Faq</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look</p>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <div class="accordion-area">
                    <div class="accordion" id="accordionExample">
                        <div class="accordion-item">
                          <h2 class="accordion-header" id="headingOne">
                            <button class="accordion-button round-bg" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour</button>
                          </h2>
                          <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                              <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses dictionary over 200 Latin words <a class="color-acordion" href="#">combined with a handful of model sentence</a> structures to generate Lorem Ipsum which </p>
                            </div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header" id="headingTwo">
                            <button class="accordion-button collapsed round-bg" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">Words which don't look even slightly believable. If you are going to use a passage of you need to be sure?</button>
                          </h2>
                          <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses dictionary over 200 Latin words <a class="color-acordion" href="#">combined with a handful of model sentence</a> structures to generate Lorem Ipsum which </p>
                            </div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header " id="headingThree">
                            <button class="accordion-button collapsed round-bg" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">Lorem Ipsum available, but the majority have suffered alteration in some form? </button>
                          </h2>
                          <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses dictionary over 200 Latin words <a class="color-acordion" href="#">combined with a handful of model sentence</a> structures to generate Lorem Ipsum which </p>
                            </div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header " id="headingfour">
                            <button class="accordion-button collapsed round-bg" type="button" data-bs-toggle="collapse" data-bs-target="#collapsefour" aria-expanded="false" aria-controls="collapsefour">Which don't look even slightly believable. If you are going to use a passage of you need to be sure?</button>
                          </h2>
                          <div id="collapsefour" class="accordion-collapse collapse" aria-labelledby="headingfour" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses dictionary over 200 Latin words <a class="color-acordion" href="#">combined with a handful of model sentence</a> structures to generate Lorem Ipsum which </p>
                            </div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header " id="headingfive">
                            <button class="accordion-button collapsed round-bg" type="button" data-bs-toggle="collapse" data-bs-target="#collapsefive" aria-expanded="false" aria-controls="collapsefour">Words which don't look even slightly believable. If you are going to use a passage of you need to be sure?</button>
                          </h2>
                          <div id="collapsefive" class="accordion-collapse collapse" aria-labelledby="headingfive" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses dictionary over 200 Latin words <a class="color-acordion" href="#">combined with a handful of model sentence</a> structures to generate Lorem Ipsum which </p>
                            </div>
                          </div>
                        </div>
                     </div>
                 </div>
            </div>
        </div>
    </div>
</section>
<!--  faq Area End   -->
<!--  Cntact  Area Start  -->
<section class="contact-us-area" id="contact">
    <div class="container-xl">
        <div class="row">
            <div class="col-lg-12">
                <div class="lan-contact">
                    <div class="contact-left text-center">
                        <h3>Contact us with any questions</h3>
                        <a class="contact-us-btn" href="#">Contact Us</a>
                    </div>
                    <div class="contact-right">
                        <div class="envolepe-messeage">
                            <img src="../assets/image/envelope.png" alt="image">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<!--  Contact Area End   -->
</template>

<script setup>
</script>

<style scoped>
/* Add any custom styling for the body here */
</style>

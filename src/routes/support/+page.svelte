<script lang="ts">
    import type { PageData } from './$types';
    
    export let data: PageData;
</script>

<!-- Breadcrumb start -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="breadcrumb-section overflow-hidden">
                    <div class="col-lg-12">
                        <div class="main-content flex items-center flex-wrap gap-3 justify-between">
                            <h2>Support</h2>
                            <div class="breadcrumb-area">
                                <nav aria-label="breadcrumb">
                                    <ol class="breadcrumb flex items-center">
                                        <li class="breadcrumb-item"><a href="dashboard.html">Home</a></li>
                                        <li class="breadcrumb-item active" aria-current="page">Support</li>
                                    </ol>
                                </nav>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Breadcrumb end -->

    <!-- Support Area start -->
    <section class=" pb-120">
        <div class="support-section relative mt-4">
            <div class="container-fruid pb-120">
                <div class="row">
                    <div class="col-lg-6">
                        <div class="top-area mb-auto">
                            <div class="section-text">
                                <h6 class="sub-title">Get in Touch</h6>
                                <h4 class="title">Any thing to say</h4>
                                <p>Feel free to send us a note with your queries or specific information you need.</p>
                            </div>
                            <div class="call-info">
                                <h6 class="lgtxt">Call Us for info</h6>
                                <a href="tel:+2295550109" class="xltxt mt-2 flex gap-2">
                                    <span class="image-area">
                                        <img src="images/icon/call.png" alt="image">
                                    </span>
                                    (229) 555-0109
                                </a>
                            </div>
                        </div>
                        <div class="sec-area absolute">
                            <img src="images/contact-us-illus.png" alt="image">
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <form id="contact">
                            <h6>Fill-up Your Information</h6>
                            <div class="input-box-area">
                                <div class="form-control">
                                    <label class="mdtxt" for="supportname">Name*</label>
                                    <input type="text" id="supportname" placeholder="Enter your name">
                                </div>
                                <div class="form-control">
                                    <label class="mdtxt" for="supportemail">Email*</label>
                                    <input type="text" id="supportemail" placeholder="Enter your email">
                                </div>
                                <div class="form-control">
                                    <label class="mdtxt" for="supportmessage">Message*</label>
                                    <textarea id="supportmessage" cols="20" rows="5" placeholder="Write your message here...."></textarea>
                                </div>
                            </div>
                            <div class="btn-area" id="contact_submit">
                                <p class="errorget"></p>
                                <button type="submit" class="cmn-btn mt-3">Send Message</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Support Area end -->

    <!-- FAQs start -->
    <section class="">
        <div class="overlay pb-120">
            <div class="container-fruid">
                <div class="row justify-center">
                    <div class="col-xl-8">
                        <div class="faqs-section support overflow-hidden">
                            <div class="row justify-center items-center">
                                <div class="col-lg-10">
                                    <div class="section-header text-center">
                                        <h6 class="sub-title">Questions and Answer</h6>
                                        <h3 class="title">Frequently asked questions</h3>
                                        <p>We would love to answer your questions, some of them are here so that you may quickly go through them. If you have any other queries <a href="{void(0)}">contact us.</a></p>
                                    </div>
                                </div>
                            </div>
                            <!-- TODO tab here -->
                            <div class="faq-box">
                                <ul class="nav mb-4 flex flex-wrap" role="tablist">
                                    <li class="nav-item" role="presentation">
                                        <button class="nav-link cmn-btn active" id="faqs-tab" data-bs-toggle="tab" data-bs-target="#faqs" type="button"
                                            role="tab" aria-controls="faqs" aria-selected="true">
                                            <span class="mdtxt">FAQs</span>
                                        </button>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <button class="nav-link cmn-btn alt" id="redeeming-coins-tab" data-bs-toggle="tab" data-bs-target="#redeeming-coins" type="button"
                                            role="tab" aria-controls="redeeming-coins" aria-selected="false">
                                            <span class="mdtxt">Redeeming Your Coins</span>
                                        </button>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <button class="nav-link cmn-btn alt" id="rarning-coins-tab" data-bs-toggle="tab" data-bs-target="#rarning-coins" type="button"
                                            role="tab" aria-controls="rarning-coins" aria-selected="false">
                                            <span class="mdtxt">Earning Coins</span>
                                        </button>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <button class="nav-link cmn-btn alt" id="offerwalls-tab" data-bs-toggle="tab" data-bs-target="#offerwalls" type="button"
                                            role="tab" aria-controls="offerwalls" aria-selected="false">
                                            <span class="mdtxt">Contact Offerwalls</span>
                                        </button>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <button class="nav-link cmn-btn alt" id="policies-tab" data-bs-toggle="tab" data-bs-target="#policies" type="button"
                                            role="tab" aria-controls="policies" aria-selected="false">
                                            <span class="mdtxt">Policies</span>
                                        </button>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <button class="nav-link cmn-btn alt" id="account-tab" data-bs-toggle="tab" data-bs-target="#account" type="button"
                                            role="tab" aria-controls="account" aria-selected="false">
                                            <span class="mdtxt">Account</span>
                                        </button>
                                    </li>
                                </ul>
                                <!-- TODO accordion -->
                                <div class="tab-content">
                                    <div class="tab-pane fade show active" id="faqs" role="tabpanel" aria-labelledby="faqs-tab">
                                        <div class="accordion" id="accordionFaqs">
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="headingOne">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#collapseOne"
                                                        aria-expanded="false" aria-controls="collapseOne">
                                                        What is Ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="collapseOne" class="accordion-collapse collapse"
                                                    aria-labelledby="headingOne" data-bs-parent="#accordionFaqs">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="headingTwo">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#collapseTwo"
                                                        aria-expanded="false" aria-controls="collapseTwo">
                                                        What are coins? How do I redeem them?
                                                    </button>
                                                </h5>
                                                <div id="collapseTwo" class="accordion-collapse collapse"
                                                    aria-labelledby="headingTwo" data-bs-parent="#accordionFaqs">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="headingThree">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#collapseThree"
                                                        aria-expanded="false" aria-controls="collapseThree">
                                                        How do I get started?
                                                    </button>
                                                </h5>
                                                <div id="collapseThree" class="accordion-collapse collapse"
                                                    aria-labelledby="headingThree" data-bs-parent="#accordionFaqs">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="headingFour">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#collapseFour"
                                                        aria-expanded="false" aria-controls="collapseFour">
                                                        Do you own all the offerwalls on this site?
                                                    </button>
                                                </h5>
                                                <div id="collapseFour" class="accordion-collapse collapse"
                                                    aria-labelledby="headingFour" data-bs-parent="#accordionFaqs">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="headingFive">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#collapseFive"
                                                        aria-expanded="false" aria-controls="collapseFive">
                                                        Are surveys safe?
                                                    </button>
                                                </h5>
                                                <div id="collapseFive" class="accordion-collapse collapse"
                                                    aria-labelledby="headingFive" data-bs-parent="#accordionFaqs">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="tab-pane fade" id="redeeming-coins" role="tabpanel" aria-labelledby="redeeming-coins-tab">
                                        <div class="accordion" id="redeeming-coins-accordion">
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="redeeming-coins-headingOne">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#redeeming-coins-collapseOne"
                                                        aria-expanded="false" aria-controls="redeeming-coins-collapseOne">
                                                        How to make money on ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="redeeming-coins-collapseOne" class="accordion-collapse collapse"
                                                    aria-labelledby="redeeming-coins-headingOne" data-bs-parent="#redeeming-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="redeeming-coins-headingTwo">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#redeeming-coins-collapseTwo"
                                                        aria-expanded="false" aria-controls="redeeming-coins-collapseTwo">
                                                        How is ugetpaid able to pay users?
                                                    </button>
                                                </h5>
                                                <div id="redeeming-coins-collapseTwo" class="accordion-collapse collapse"
                                                    aria-labelledby="redeeming-coins-headingTwo" data-bs-parent="#redeeming-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="redeeming-coins-headingThree">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#redeeming-coins-collapseThree"
                                                        aria-expanded="false" aria-controls="redeeming-coins-collapseThree">
                                                        How long does it take to cash out your money?
                                                    </button>
                                                </h5>
                                                <div id="redeeming-coins-collapseThree" class="accordion-collapse collapse"
                                                    aria-labelledby="redeeming-coins-headingThree" data-bs-parent="#redeeming-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="redeeming-coins-headingFour">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#redeeming-coins-collapseFour"
                                                        aria-expanded="false" aria-controls="redeeming-coins-collapseFour">
                                                        What are Terms and Conditions and Privacy Policy?
                                                    </button>
                                                </h5>
                                                <div id="redeeming-coins-collapseFour" class="accordion-collapse collapse"
                                                    aria-labelledby="redeeming-coins-headingFour" data-bs-parent="#redeeming-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="redeeming-coins-headingFive">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#redeeming-coins-collapseFive"
                                                        aria-expanded="false" aria-controls="redeeming-coins-collapseFive">
                                                        How much money can you really earn on ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="redeeming-coins-collapseFive" class="accordion-collapse collapse"
                                                    aria-labelledby="redeeming-coins-headingFive" data-bs-parent="#redeeming-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="tab-pane fade" id="rarning-coins" role="tabpanel" aria-labelledby="rarning-coins-tab">
                                        <div class="accordion" id="earning-coins-accordion">
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="earning-coins-headingOne">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#earning-coins-collapseOne"
                                                        aria-expanded="false" aria-controls="earning-coins-collapseOne">
                                                        What is Ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="earning-coins-collapseOne" class="accordion-collapse collapse"
                                                    aria-labelledby="earning-coins-headingOne" data-bs-parent="#earning-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="earning-coins-headingTwo">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#earning-coins-collapseTwo"
                                                        aria-expanded="false" aria-controls="earning-coins-collapseTwo">
                                                        What are coins? How do I redeem them?
                                                    </button>
                                                </h5>
                                                <div id="earning-coins-collapseTwo" class="accordion-collapse collapse"
                                                    aria-labelledby="earning-coins-headingTwo" data-bs-parent="#earning-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="earning-coins-headingThree">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#earning-coins-collapseThree"
                                                        aria-expanded="false" aria-controls="earning-coins-collapseThree">
                                                        How do I get started?
                                                    </button>
                                                </h5>
                                                <div id="earning-coins-collapseThree" class="accordion-collapse collapse"
                                                    aria-labelledby="earning-coins-headingThree" data-bs-parent="#earning-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="earning-coins-headingFour">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#earning-coins-collapseFour"
                                                        aria-expanded="false" aria-controls="earning-coins-collapseFour">
                                                        Do you own all the offerwalls on this site?
                                                    </button>
                                                </h5>
                                                <div id="earning-coins-collapseFour" class="accordion-collapse collapse"
                                                    aria-labelledby="earning-coins-headingFour" data-bs-parent="#earning-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="earning-coins-headingFive">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#earning-coins-collapseFive"
                                                        aria-expanded="false" aria-controls="earning-coins-collapseFive">
                                                        Are surveys safe?
                                                    </button>
                                                </h5>
                                                <div id="earning-coins-collapseFive" class="accordion-collapse collapse"
                                                    aria-labelledby="earning-coins-headingFive" data-bs-parent="#earning-coins-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="tab-pane fade" id="offerwalls" role="tabpanel" aria-labelledby="offerwalls-tab">
                                        <div class="accordion" id="offerwalls-accordion">
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="offerwalls-headingOne">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#offerwalls-collapseOne"
                                                        aria-expanded="false" aria-controls="offerwalls-collapseOne">
                                                        How to make money on ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="offerwalls-collapseOne" class="accordion-collapse collapse"
                                                    aria-labelledby="offerwalls-headingOne" data-bs-parent="#offerwalls-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="offerwalls-headingTwo">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#offerwalls-collapseTwo"
                                                        aria-expanded="false" aria-controls="offerwalls-collapseTwo">
                                                        How is ugetpaid able to pay users?
                                                    </button>
                                                </h5>
                                                <div id="offerwalls-collapseTwo" class="accordion-collapse collapse"
                                                    aria-labelledby="offerwalls-headingTwo" data-bs-parent="#offerwalls-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="offerwalls-headingThree">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#offerwalls-collapseThree"
                                                        aria-expanded="false" aria-controls="offerwalls-collapseThree">
                                                        How long does it take to cash out your money?
                                                    </button>
                                                </h5>
                                                <div id="offerwalls-collapseThree" class="accordion-collapse collapse"
                                                    aria-labelledby="offerwalls-headingThree" data-bs-parent="#offerwalls-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="offerwalls-headingFour">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#offerwalls-collapseFour"
                                                        aria-expanded="false" aria-controls="offerwalls-collapseFour">
                                                        What are Terms and Conditions and Privacy Policy?
                                                    </button>
                                                </h5>
                                                <div id="offerwalls-collapseFour" class="accordion-collapse collapse"
                                                    aria-labelledby="offerwalls-headingFour" data-bs-parent="#offerwalls-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="offerwalls-headingFive">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#offerwalls-collapseFive"
                                                        aria-expanded="false" aria-controls="offerwalls-collapseFive">
                                                        How much money can you really earn on ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="offerwalls-collapseFive" class="accordion-collapse collapse"
                                                    aria-labelledby="offerwalls-headingFive" data-bs-parent="#offerwalls-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="tab-pane fade" id="policies" role="tabpanel" aria-labelledby="policies-tab">
                                        <div class="accordion" id="policies-accordion">
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="policies-headingOne">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#policies-collapseOne"
                                                        aria-expanded="false" aria-controls="policies-collapseOne">
                                                        What is Ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="policies-collapseOne" class="accordion-collapse collapse"
                                                    aria-labelledby="policies-headingOne" data-bs-parent="#policies-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="policies-headingTwo">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#policies-collapseTwo"
                                                        aria-expanded="false" aria-controls="policies-collapseTwo">
                                                        What are coins? How do I redeem them?
                                                    </button>
                                                </h5>
                                                <div id="policies-collapseTwo" class="accordion-collapse collapse"
                                                    aria-labelledby="policies-headingTwo" data-bs-parent="#policies-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="policies-headingThree">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#policies-collapseThree"
                                                        aria-expanded="false" aria-controls="policies-collapseThree">
                                                        How do I get started?
                                                    </button>
                                                </h5>
                                                <div id="policies-collapseThree" class="accordion-collapse collapse"
                                                    aria-labelledby="policies-headingThree" data-bs-parent="#policies-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="policies-headingFour">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#policies-collapseFour"
                                                        aria-expanded="false" aria-controls="policies-collapseFour">
                                                        Do you own all the offerwalls on this site?
                                                    </button>
                                                </h5>
                                                <div id="policies-collapseFour" class="accordion-collapse collapse"
                                                    aria-labelledby="policies-headingFour" data-bs-parent="#policies-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="policies-headingFive">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#policies-collapseFive"
                                                        aria-expanded="false" aria-controls="policies-collapseFive">
                                                        Are surveys safe?
                                                    </button>
                                                </h5>
                                                <div id="policies-collapseFive" class="accordion-collapse collapse"
                                                    aria-labelledby="policies-headingFive" data-bs-parent="#policies-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="tab-pane fade" id="account" role="tabpanel" aria-labelledby="account-tab">
                                        <div class="accordion" id="account-accordion">
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="account-headingOne">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#account-collapseOne"
                                                        aria-expanded="false" aria-controls="account-collapseOne">
                                                        How to make money on ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="account-collapseOne" class="accordion-collapse collapse"
                                                    aria-labelledby="account-headingOne" data-bs-parent="#account-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="account-headingTwo">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#account-collapseTwo"
                                                        aria-expanded="false" aria-controls="account-collapseTwo">
                                                        How is ugetpaid able to pay users?
                                                    </button>
                                                </h5>
                                                <div id="account-collapseTwo" class="accordion-collapse collapse"
                                                    aria-labelledby="account-headingTwo" data-bs-parent="#account-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="account-headingThree">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#account-collapseThree"
                                                        aria-expanded="false" aria-controls="account-collapseThree">
                                                        How long does it take to cash out your money?
                                                    </button>
                                                </h5>
                                                <div id="account-collapseThree" class="accordion-collapse collapse"
                                                    aria-labelledby="account-headingThree" data-bs-parent="#account-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="account-headingFour">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#account-collapseFour"
                                                        aria-expanded="false" aria-controls="account-collapseFour">
                                                        What are Terms and Conditions and Privacy Policy?
                                                    </button>
                                                </h5>
                                                <div id="account-collapseFour" class="accordion-collapse collapse"
                                                    aria-labelledby="account-headingFour" data-bs-parent="#account-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="accordion-item">
                                                <h5 class="accordion-header lgtxt" id="account-headingFive">
                                                    <button class="accordion-button collapsed" type="button"
                                                        data-bs-toggle="collapse" data-bs-target="#account-collapseFive"
                                                        aria-expanded="false" aria-controls="account-collapseFive">
                                                        How much money can you really earn on ugetpaid?
                                                    </button>
                                                </h5>
                                                <div id="account-collapseFive" class="accordion-collapse collapse"
                                                    aria-labelledby="account-headingFive" data-bs-parent="#account-accordion">
                                                    <div class="accordion-body">
                                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
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
            </div>
        </div>
    </section>
    <!-- FAQs end -->

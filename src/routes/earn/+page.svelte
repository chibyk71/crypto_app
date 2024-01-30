<script lang="ts">
    import type { PageData } from './$types';
    
    export let data: PageData;
</script>


    <!-- Start Offer Popup start -->
    <!-- TODO create modal -->
    <div class="start-offer-popup cmn-popup hidden">
        <div class="container-fruid">
            <div class="row">
                <div class="col-lg-6">
                    <div class="modal fade" id="startOfferMod" aria-hidden="true" >
                        <div class="modal-dialog modal-dialog-centered relative">
                            <div class="modal-content">
                                <div class="modal-header justify-between absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="main-content">
                                    <div class="head-area flex flex-wrap gap-3 justify-between items-center">
                                        <div class="left-area flex gap-3 items-center">
                                            <div class="icon-area">
                                                <img src="images/featured-img-6.png" alt="icon">
                                            </div>
                                            <h3 class="m-0">Hexagon</h3>
                                        </div>
                                        <div class="option-area flex-wrap gap-2">
                                            <div class="single-box">
                                                <div class="icon-area">
                                                    <img src="images/icon/android.png" alt="icon">
                                                </div>
                                                $0.10
                                            </div>
                                            <div class="single-box">
                                                <div class="icon-area">
                                                    <img src="images/icon/apple.png" alt="icon">
                                                </div>
                                                $0.10
                                            </div>
                                            <div class="single-box">
                                                <div class="icon-area">
                                                    <img src="images/icon/pc.png" alt="icon">
                                                </div>
                                                $0.10
                                            </div>
                                            <a href="{void(0)}" class="cmn-btn">Start Offer</a>
                                        </div>
                                    </div>
                                    <div class="content-box">
                                        <div class="single">
                                            <h6 class="title">Description</h6>
                                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eget feugiat id massa. Risus ultricies feugiat amet ut lectus aliquet. Vulputate interdum commodo enim ipsum cras aliquam. Viverra ut molestie nisl consectetur tristique.</p>
                                        </div>
                                        <div class="single mt-5">
                                            <h6 class="title">Requirements</h6>
                                            <ul>
                                                <li> Sed eget feugiat id massa. Risus ultricies feugiat amet ut lectus aliquet. </li>
                                                <li> Sed eget feugiat id massa. Risus ultricies feugiat amet ut lectus aliquet. </li>
                                                <li> Sed eget feugiat id massa. Risus ultricies feugiat amet ut lectus aliquet. </li>
                                            </ul>
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
    <!-- Start Offer Popup start -->

    <!-- Survery Popup start -->
    <!-- TODO create modal -->
    <div class="survery-popup cmn-popup hidden">
        <div class="container-fruid">
            <div class="row">
                <div class="col-lg-6">
                    <div class="modal fade" id="surveryMod" aria-hidden="true" >
                        <div class="modal-dialog modal-dialog-centered relative">
                            <div class="modal-content">
                                <div class="modal-header justify-between absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="main-content">
                                    <div class="head-area flex flex-wrap gap-3 justify-between items-center">
                                        <div class="left-area flex gap-3 items-center">
                                            <div class="icon-area">
                                                <img src="images/survery-icon.png" alt="icon">
                                            </div>
                                            <div class="text-area">
                                                <h6 class="m-0">Hexagon survery</h6>
                                                <p class="mdtxt">Complete any offer to receive coins</p>
                                            </div>
                                        </div>
                                        <div class="option-area">
                                            <div class="icon-area">
                                                <img src="images/icon/android.png" alt="icon">
                                            </div>
                                            <div class="icon-area">
                                                <img src="images/icon/apple.png" alt="icon">
                                            </div>
                                            <div class="icon-area">
                                                <img src="images/icon/pc.png" alt="icon">
                                            </div>
                                        </div>
                                    </div>
                                    <div class="content-box">
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-1.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">Your Surveys</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>You earn 6,250 points per survey and you can complete multiple surveys per day. Complete the survey until you reach the "Thank you" page.</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
                                            </div>
                                        </div>
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-2.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">CPX Research</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>Answer profiling questions and start doing matching surveys. Check back daily for new surveys.</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
                                            </div>
                                        </div>
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-3.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">Speak Up</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>Speak Up asks you a few questions and redirects you to a survey that matches your profile. You can complete multiple surveys per day with Speak Up!</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
                                            </div>
                                        </div>
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-4.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">Theorem Reach</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>TheoremReach lets you choose between multiple surveys that match your profile. New surveys are added every day!</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
                                            </div>
                                        </div>
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-5.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">Abstract</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>Abstract shows you a variety of surveys which match your profile. Make sure to check back frequently as new surveys are added every day.</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
                                            </div>
                                        </div>
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-6.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">phoenix</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>Verify your email, complete your profiler and get access to different surveys. New surveys are added on a daily basis!</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
                                            </div>
                                        </div>
                                        <div class="single-box">
                                            <div class="left-area">
                                                <div class="icon-area">
                                                    <img src="images/survery-img-7.png" class="max-un" alt="icon">
                                                </div>
                                                <div class="text-area">
                                                    <h6 class="title">Dragon</h6>
                                                    <div class="info-area mb-3 flex items-center gap-4">
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/clock-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                        </div>
                                                        <div class="single-item">
                                                            <div class="icon-area">
                                                                <img src="images/icon/price-icon.png" alt="icon">
                                                            </div>
                                                            <span class="mdtxt">15 minutes</span>
                                                            <div class="icon-area">
                                                                <img src="images/icon/coin-icon.png" alt="icon">
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <p>Answer a few profiler questions and get access to a variety of different surveys. New surveys are added every day!</p>
                                                </div>
                                            </div>
                                            <div class="right-area">
                                                <a href="{void(0)}" class="cmn-btn">
                                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                                    Start Earning
                                                </a>
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
    <!-- Survery Popup start -->

    <!-- Latest Activites start -->
<!-- TODO carousel -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="latest-activites overflow-hidden">
                    <div class="top-bar top-bar-carousel">
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-1.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>ugetpaid</span>
                                        <p class="mdtxt">Lionel</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-2.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>lootably</span>
                                        <p class="mdtxt">Perry</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-3.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>Research</span>
                                        <p class="mdtxt">Foster</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-4.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>withdraw</span>
                                        <p class="mdtxt">LTC</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-3.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>CPX</span>
                                        <p class="mdtxt">Steven</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-2.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>Timewall</span>
                                        <p class="mdtxt">Mathis</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                        <div class="single">
                            <a href="user-profile.html" class="single-box">
                                <div class="flex gap-3 items-center">
                                    <div class="border-gradient">
                                        <img src="images/activites-img-1.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <span>withdraw</span>
                                        <p class="mdtxt">LTC</p>
                                    </div>
                                </div>
                                <p class="number">580</p>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Latest Activites end -->

    <!-- Featured Offer start -->
    <section class=" paid-surveys">
        <div class="featured-offer overflow-hidden relative">
            <div class="container-fruid pt-120 pb-120">
                <div class="bg-area absolute">
                    <div class="shape-area z-index-0">
                        <img src="images/featured-shape-1.png" class="shape shape-1" alt="shape">
                        <img src="images/featured-shape-2.png" class="shape shape-2" alt="shape">
                        <img src="images/featured-shape-3.png" class="shape shape-3" alt="shape">
                        <img src="images/featured-coin-2.png" class="coin coin-1" alt="shape">
                        <img src="images/featured-coin-1.png" class="coin coin-2" alt="shape">
                    </div>
                </div>
                <div class="row justify-center">
                    <div class="col-xl-6 col-lg-7">
                        <div class="section-header text-center">
                            <h1 class="title">Featured Offer</h1>
                            <p class="xltxt">People from your co the most of these things recently. (1000 Coins equals $1.00)</p>
                        </div>
                    </div>
                </div>
                <div class="row justify-center">
                    <div class="col-xl-12">
                        <div class="row justify-center content-areas cus-mar">
                            <div class="col-auto">
                                <div class="single-box">
                                    <div class="img-area">
                                        <img src="images/featured-img-1.png" alt="image">
                                    </div>
                                    <h6>Rolex & Giveaway</h6>
                                    <div class="btn-area flex flex-wrap justify-center gap-3">
                                        <p class="cmn-btn alt">
                                            $0.10
                                        </p>
                                        <a href="{void(0)}" class="cmn-btn" data-bs-toggle="modal" data-bs-target="#startOfferMod">
                                            Start Offer
                                        </a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-auto">
                                <div class="single-box">
                                    <div class="img-area">
                                        <img src="images/featured-img-2.png" alt="image">
                                    </div>
                                    <h6>Product Evaluation</h6>
                                    <div class="btn-area flex flex-wrap justify-center gap-3">
                                        <p class="cmn-btn alt">
                                            $0.10
                                        </p>
                                        <a href="{void(0)}" class="cmn-btn" data-bs-toggle="modal" data-bs-target="#startOfferMod">
                                            Start Offer
                                        </a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-auto">
                                <div class="single-box">
                                    <div class="img-area">
                                        <img src="images/featured-img-3.png" alt="image">
                                    </div>
                                    <h6>Saas feedback</h6>
                                    <div class="btn-area flex flex-wrap justify-center gap-3">
                                        <p class="cmn-btn alt">
                                            $0.10
                                        </p>
                                        <a href="{void(0)}" class="cmn-btn" data-bs-toggle="modal" data-bs-target="#startOfferMod">
                                            Start Offer
                                        </a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-auto">
                                <div class="single-box">
                                    <div class="img-area">
                                        <img src="images/featured-img-4.png" alt="image">
                                    </div>
                                    <h6>CPX Research</h6>
                                    <div class="btn-area flex flex-wrap justify-center gap-3">
                                        <p class="cmn-btn alt">
                                            $0.10
                                        </p>
                                        <a href="{void(0)}" class="cmn-btn" data-bs-toggle="modal" data-bs-target="#startOfferMod">
                                            Start Offer
                                        </a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-auto">
                                <div class="single-box">
                                    <div class="img-area">
                                        <img src="images/featured-img-5.png" alt="image">
                                    </div>
                                    <h6>Opinion Capital</h6>
                                    <div class="btn-area flex flex-wrap justify-center gap-3">
                                        <p class="cmn-btn alt">
                                            $0.10
                                        </p>
                                        <a href="{void(0)}" class="cmn-btn" data-bs-toggle="modal" data-bs-target="#startOfferMod">
                                            Start Offer
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Featured Offer end -->

    <!-- Offer Walls start -->
    <section class=" paid-surveys">
        <div class="offer-walls relative">
            <div class="container-fruid pb-120">
                <div class="row justify-center">
                    <div class="col-xxl-5 col-xl-6 col-lg-7">
                        <div class="section-header text-center">
                            <h2 class="title">Offer Walls</h2>
                            <p>Each Offer Wall contains hundreds of tasks to complete. Choose from one of them to start earning coins.</p>
                        </div>
                    </div>
                </div>
                <div class="row justify-custom">
                    <div class="col-auto">
                        <div class="single-box" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-1.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Hexagon</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box second" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-2.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Connect People</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box third" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-3.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Triangle</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box four" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-4.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Phoenix</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box five" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-5.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Spybats</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-6.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Flamefire</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box four" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-7.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Firefly</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box second" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-8.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Circuit</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-12">
                        <div class="btn-area mt-0 mt-sm-4 flex justify-center">
                            <a href="offerwalls.html" class="cmn-btn">
                                View All Offers
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Offer Walls end -->

    <!-- Surveys start -->
    <section class=" paid-surveys">
        <div class="offer-walls serveys relative">
            <div class="container-fruid pt-120 pb-120">
                <div class="row justify-center">
                    <div class="col-xxl-4 col-xl-5 col-lg-6">
                        <div class="section-header text-center">
                            <h2 class="title">Surveys</h2>
                            <p>Complete surveys to earn coins. You will be rewarded for each survey completed.</p>
                        </div>
                    </div>
                </div>
                <div class="row justify-custom">
                    <div class="col-auto">
                        <div class="single-box" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-1.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Hexagon</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box second" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-2.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Connect People</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box third" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-3.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Triangle</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-auto">
                        <div class="single-box four" data-bs-toggle="modal" data-bs-target="#surveryMod">
                            <div class="img-area">
                                <img src="images/offer-walls-img-4.png" alt="image">
                            </div>
                            <div class="text-area">
                                <div class="btn-area mb-3">
                                    <span class="cmn-btn alt">
                                        +50% Bonus
                                    </span>
                                </div>
                                <h6>Phoenix</h6>
                                <div class="scale mt-2 flex items-center gap-2">
                                    <span>Popularity</span>
                                    <div class="img-area">
                                        <img src="images/icon/usa-flag.png" class="max-un" alt="image">
                                    </div>
                                    <span>80</span>
                                </div>
                                <div class="progress">
                                    <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-12">
                        <div class="btn-area mt-0 mt-sm-4 flex justify-center">
                            <a href="surveys.html" class="cmn-btn">
                                View All Surveys
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Surveys end -->

    <!-- Watch Videos start -->
    <section class="">
        <div class="watch-videos relative">
            <div class="container-fruid pt-120 pb-120">
                <div class="row cus-mar">
                    <div class="col-xl-4 col-md-6">
                        <div class="single-box">
                            <div class="icon-area">
                                <img src="images/icon/watch-videos-icon-1.png" alt="image">
                            </div>
                            <h2>Watch Videos</h2>
                            <p class="mdtxt">Watch unlimited videos.</p>
                            <div class="text-area">
                                <div class="btn-area mt-4">
                                    <a href="{void(0)}" class="cmn-btn">
                                        Watch Videos Start Earning
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6">
                        <div class="single-box second">
                            <div class="icon-area">
                                <img src="images/icon/watch-videos-icon-2.png" alt="image">
                            </div>
                            <h2>Referrals</h2>
                            <p class="mdtxt">Get your referral link and invite friends.</p>
                            <div class="text-area">
                                <div class="btn-area mt-4">
                                    <a href="{void(0)}" class="cmn-btn">
                                        Invite Now
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6">
                        <div class="single-box third">
                            <div class="icon-area">
                                <img src="images/icon/watch-videos-icon-3.png" alt="image">
                            </div>
                            <h2>Promotions</h2>
                            <p class="mdtxt">Do Idle-Empire special promotions.</p>
                            <div class="text-area">
                                <div class="btn-area mt-4">
                                    <a href="{void(0)}" class="cmn-btn">
                                        Watch Videos Start Earning
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Watch Videos end -->

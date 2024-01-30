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
                            <h2>Giveaway</h2>
                            <div class="breadcrumb-area">
                                <nav aria-label="breadcrumb">
                                    <ol class="breadcrumb flex items-center">
                                        <li class="breadcrumb-item"><a href="dashboard.html">Home</a></li>
                                        <li class="breadcrumb-item active" aria-current="page">Giveaway</li>
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

    <!-- Giveaway Section start -->
    <section class="">
        <div class="giveaway-section mt-4">
            <div class="container-fruid pb-120">
                <div class="row justify-center">
                    <div class="col-lg-7">
                        <div class="section-text text-center">
                            <h5>You can win money</h5>
                            <h1>$100,000</h1>
                        </div>
                        <div class="btn-area flex flex-wrap gap-3 mb-5 justify-center">
                            <button class="cmn-btn" data-bs-toggle="modal" data-bs-target="#openDailyCases">Open Daily Cases</button>
                            <button class="cmn-btn alt" data-bs-toggle="modal" data-bs-target="#giveawayPopup">Enter $10,000 Giveaway</button>
                        </div>
                    </div>
                </div>
                <div class="row justify-center">
                    <div class="col-xl-6 col-lg-8 col-md-9 col-11">
                        <div class="prizes-win-carousel">
                            <div class="single-content">
                                <div class="single-slide">
                                    <div class="img-area">
                                        <img src="images/icon/slider-icon.png" alt="image">
                                    </div>
                                    <h6 class="lgtxt">The prizes you can win vary daily and  range</h6>
                                    <h5>From $0,25 to $599</h5>
                                </div>
                            </div>
                            <div class="single-content">
                                <div class="single-slide">
                                    <div class="img-area">
                                        <img src="images/icon/slider-icon.png" alt="image">
                                    </div>
                                    <h6 class="lgtxt">The prizes you can win vary daily and  range</h6>
                                    <h5>From $0,25 to $599</h5>
                                </div>
                            </div>
                            <div class="single-content">
                                <div class="single-slide">
                                    <div class="img-area">
                                        <img src="images/icon/slider-icon.png" alt="image">
                                    </div>
                                    <h6 class="lgtxt">The prizes you can win vary daily and  range</h6>
                                    <h5>From $0,25 to $599</h5>
                                </div>
                            </div>
                            <div class="single-content">
                                <div class="single-slide">
                                    <div class="img-area">
                                        <img src="images/icon/slider-icon.png" alt="image">
                                    </div>
                                    <h6 class="lgtxt">The prizes you can win vary daily and  range</h6>
                                    <h5>From $0,25 to $599</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Giveaway Section end -->

    <!-- Open Daily Cases Popup start -->
    <!-- TODO modal -->
    <div class="daily-cases-popup cmn-popup hidden">
        <div class="container-fruid">
            <div class="row">
                <div class="col-lg-6">
                    <div class="modal fade" id="openDailyCases" aria-hidden="true" >
                        <div class="modal-dialog modal-dialog-centered relative">
                            <div class="modal-content">
                                <div class="modal-header justify-between absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="main-content daily-winners">
                                    <div class="head-area text-center">
                                        <h4>Open Daily Cases</h4>
                                    </div>
                                    <div class="content-box mt-4">
                                        <ul class="nav" role="tablist">
                                            <li class="nav-item" role="presentation">
                                                <button class="nav-link active" id="daily-cases-1st-tab" data-bs-toggle="tab" data-bs-target="#daily-cases-1st" type="button"
                                                    role="tab" aria-controls="daily-cases-1st" aria-selected="true">
                                                    <span class="border-area">
                                                        <span class="lgtxt">
                                                            <img src="images/icon/coin-box-1.png" alt="icon">
                                                        </span>
                                                    </span>
                                                    <span class="total-earn">Earn 0/1,000 coins</span>
                                                    <span class="cmn-btn">
                                                        <img src="images/icon/lock-icon.png" alt="icon">
                                                        View Winners
                                                    </span>
                                                </button>
                                            </li>
                                            <li class="nav-item" role="presentation">
                                                <button class="nav-link" id="daily-cases-2nd-tab" data-bs-toggle="tab" data-bs-target="#daily-cases-2nd" type="button"
                                                    role="tab" aria-controls="daily-cases-2nd" aria-selected="false">
                                                    <span class="border-area">
                                                        <span class="lgtxt">
                                                            <img src="images/icon/coin-box-2.png" alt="icon">
                                                        </span>
                                                    </span>
                                                    <span class="total-earn">Earn 0/5,000 coins</span>
                                                    <span class="cmn-btn alt">
                                                        <img src="images/icon/lock-icon.png" alt="icon">
                                                        View Winners
                                                    </span>
                                                </button>
                                            </li>
                                            <li class="nav-item" role="presentation">
                                                <button class="nav-link" id="daily-cases-3rd-tab" data-bs-toggle="tab" data-bs-target="#daily-cases-3rd" type="button"
                                                    role="tab" aria-controls="daily-cases-3rd" aria-selected="false">
                                                    <span class="border-area">
                                                        <span class="lgtxt">
                                                            <img src="images/icon/coin-box-3.png" alt="icon">
                                                        </span>
                                                    </span>
                                                    <span class="total-earn">Earn 0/25,000 coins</span>
                                                    <span class="cmn-btn alt">
                                                        <img src="images/icon/lock-icon.png" alt="icon">
                                                        View Winners
                                                    </span>
                                                </button>
                                            </li>
                                        </ul>
                                        <p class="separator mdtxt">Contains</p>
                                        <div class="tab-content">
                                            <div class="tab-pane fade show active" id="daily-cases-1st" role="tabpanel" aria-labelledby="daily-cases-1st-tab">
                                                <div class="content-area cus-mar">
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-1.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-2.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-3.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-1.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-3.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-5.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="tab-pane fade" id="daily-cases-2nd" role="tabpanel" aria-labelledby="daily-cases-2nd-tab">
                                                <div class="content-area cus-mar">
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-1.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-2.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-3.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-1.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-3.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-5.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="tab-pane fade" id="daily-cases-3rd" role="tabpanel" aria-labelledby="daily-cases-3rd-tab">
                                                <div class="content-area cus-mar">
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-1.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-2.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-3.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-1.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-3.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-5.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
                                                    </div>
                                                    <div class="single-box">
                                                        <div class="image-area">
                                                            <img src="images/winners-item-4.png" alt="image">
                                                        </div>
                                                        <p class="mdtxt">$250.00</p>
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
    </div>
    <!-- Open Daily Cases Popup start -->

    <!-- Giveaway Popup start -->
    <!-- TODO modal -->
    <div class="giveaway-popup cmn-popup">
        <div class="container-fruid">
            <div class="row">
                <div class="col-lg-6">
                    <div class="modal fade" id="giveawayPopup" aria-hidden="true" >
                        <div class="modal-dialog modal-dialog-centered relative">
                            <div class="modal-content">
                                <div class="modal-header justify-between absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="main-content">
                                    <div class="content-box text-center">
                                        <div class="img-area">
                                            <img src="images/icon/giveaway-icon.png" alt="image">
                                        </div>
                                        <div class="section-header mt-5">
                                            <h5 class="title">$7500 Rolex Giveaway + 5x $500</h5>
                                            <p class="mdtxt">Good luck to everyone! There will be 6 winners in total. Cheating with the earn coins tasks will result in a re-roll.</p>
                                        </div>
                                        <div class="winners-area">
                                            <div class="single-box">
                                                <h5>0</h5>
                                                <p class="mdtxt">Your Entries</p>
                                            </div>
                                            <div class="single-box">
                                                <h5>8135250</h5>
                                                <p class="mdtxt">Total Entries</p>
                                            </div>
                                            <div class="single-box">
                                                <h5>15</h5>
                                                <p class="mdtxt">Days Left</p>
                                            </div>
                                        </div>
                                        <div class="btn-area mt-4">
                                            <a href="{void(0)}" class="cmn-btn">Join Now</a>
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
    <!-- Giveaway Popup start -->

    <!-- Top 24 winners start -->
    <!-- TODO carousel -->
    <section class="">
        <div class="top-24-winners">
            <div class="container-fruid pb-120">
                <h3>Top winners last 24 hours</h3>
                <div class="top-24-winners-carousel">
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-1.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-1.png" alt="image">
                                </div>
                                <span class="mdtxt">lazy616</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-2.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-2.png" alt="image">
                                </div>
                                <span class="mdtxt">purplel757</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-3.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-3.png" alt="image">
                                </div>
                                <span class="mdtxt">purplel757</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-3.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-4.png" alt="image">
                                </div>
                                <span class="mdtxt">happys594</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-4.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-5.png" alt="image">
                                </div>
                                <span class="mdtxt">silverlion355</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-5.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-6.png" alt="image">
                                </div>
                                <span class="mdtxt">fulmouse112</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-3.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-7.png" alt="image">
                                </div>
                                <span class="mdtxt">sadpanda176</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-5.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-3.png" alt="image">
                                </div>
                                <span class="mdtxt">brownbear646</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-2.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-4.png" alt="image">
                                </div>
                                <span class="mdtxt">silverduck204</span>
                            </div>
                        </div>
                    </div>
                    <div class="single-content">
                        <div class="single-slide">
                            <div class="icon-area">
                                <img src="images/winners-item-1.png" alt="image">
                            </div>
                            <p class="mdtxt">$250.00</p>
                            <div class="profile-area flex items-center justify-center gap-2">
                                <div class="img-area">
                                    <img src="images/winners-image-5.png" alt="image">
                                </div>
                                <span class="mdtxt">lazy616</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Top 24 winners end -->

    <!-- Daily Winners start -->
    <section class=" pb-120">
        <div class="daily-winners">
            <div class="container-fruid pt-120">
                <div class="row justify-center">
                    <div class="col-lg-8">
                        <div class="section-header text-center">
                            <h4>Top Daily Winners</h4>
                        </div>
                    </div>
                </div>
                <ul class="nav daily-winners-carousel" role="tablist">
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link active" id="view-1st-tab" data-bs-toggle="tab" data-bs-target="#view-1st" type="button"
                                role="tab" aria-controls="view-1st" aria-selected="true">
                                <span class="border-area">
                                    <span class="lgtxt">1st</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-2nd-tab" data-bs-toggle="tab" data-bs-target="#view-2nd" type="button"
                                role="tab" aria-controls="view-2nd" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">2nd</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-3rd-tab" data-bs-toggle="tab" data-bs-target="#view-3rd" type="button"
                                role="tab" aria-controls="view-3rd" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">3rd</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-4th-tab" data-bs-toggle="tab" data-bs-target="#view-4th" type="button"
                                role="tab" aria-controls="view-4th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">4th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-5th-tab" data-bs-toggle="tab" data-bs-target="#view-5th" type="button"
                                role="tab" aria-controls="view-5th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">5th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-6th-tab" data-bs-toggle="tab" data-bs-target="#view-6th" type="button"
                                role="tab" aria-controls="view-6th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">6th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-7th-tab" data-bs-toggle="tab" data-bs-target="#view-7th" type="button"
                                role="tab" aria-controls="view-7th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">7th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-8th-tab" data-bs-toggle="tab" data-bs-target="#view-8th" type="button"
                                role="tab" aria-controls="view-8th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">8th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-9th-tab" data-bs-toggle="tab" data-bs-target="#view-9th" type="button"
                                role="tab" aria-controls="view-9th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">9th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                    <li class="nav-item" role="presentation">
                        <span class="link-head">
                            <button class="nav-link" id="view-10th-tab" data-bs-toggle="tab" data-bs-target="#view-10th" type="button"
                                role="tab" aria-controls="view-10th" aria-selected="false">
                                <span class="border-area">
                                    <span class="lgtxt">10th</span>
                                    <span class="mdtxt">Closed</span>
                                </span>
                                <span class="cmn-btn alt">View Winners</span>
                            </button>
                        </span>
                    </li>
                </ul>
                <div class="tab-content mt-3">
                    <div class="tab-pane fade show active" id="view-1st" role="tabpanel" aria-labelledby="view-1st-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-2nd" role="tabpanel" aria-labelledby="view-2nd-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-3rd" role="tabpanel" aria-labelledby="view-3rd-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-4th" role="tabpanel" aria-labelledby="view-4th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-5th" role="tabpanel" aria-labelledby="view-5th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-6th" role="tabpanel" aria-labelledby="view-6th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-7th" role="tabpanel" aria-labelledby="view-7th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-8th" role="tabpanel" aria-labelledby="view-8th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-9th" role="tabpanel" aria-labelledby="view-9th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tab-pane fade" id="view-10th" role="tabpanel" aria-labelledby="view-10th-tab">
                        <div class="row gap-4 gap-xxl-0">
                            <div class="col-xxl-3 col-lg-5 col-md-7 col-sm-8">
                                <div class="top-winners">
                                    <div class="head-item flex flex-wrap justify-center items-center gap-2">
                                        <span class="image-area">
                                            <img src="images/icon/crown-kings-2.png" alt="icon">
                                        </span>
                                        <h6 class="m-0">Top Winners</h6>
                                    </div>
                                    <div class="single-item">
                                        <h5>$3,726.00</h5>
                                        <p class="m-0">Won</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>2123</h5>
                                        <p class="m-0">Winner</p>
                                    </div>
                                    <div class="single-item">
                                        <h5>$1.76</h5>
                                        <p class="m-0">Average Reward</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xxl-9">
                                <div class="row gap-0 ga-md-4">
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">wolf227</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-4.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-md-6">
                                        <ul>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-6.png" alt="image">
                                                    </span>
                                                    <span class="m-0">brownfish258</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-7.png" alt="image">
                                                    </span>
                                                    <span class="m-0">butterfly101</span>
                                                </a>
                                                <p>$375 Gucci wallet</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-5.png" alt="image">
                                                    </span>
                                                    <span class="m-0">whitefish664</span>
                                                </a>
                                                <p>$150 Airpods</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-1.png" alt="image">
                                                    </span>
                                                    <span class="m-0">swan732</span>
                                                </a>
                                                <p>$100 PayPal Giftcard</p>
                                            </li>
                                            <li>
                                                <a href="user-profile.html" class="left-area">
                                                    <span class="image-area">
                                                        <img src="images/table-img-3.png" alt="image">
                                                    </span>
                                                    <span class="m-0">silver195</span>
                                                </a>
                                                <p>$50 Visa Giftcard </p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Daily Winners end -->

    <!-- TODO both carousel and tab -->
    <!-- Winners Drawing start -->
    <section class=" pb-120">
        <div class="winners-drawing">
            <div class="container-fruid">
                <div class="row justify-center">
                    <div class="col-lg-8">
                        <div class="section-header text-center">
                            <h3>Winners Drawing In</h3>
                        </div>
                    </div>
                </div>
                <div class="row cus-mar justify-center">
                    <div class="col-xl-4 col-md-6">
                        <div class="single-box">
                            <div class="img-area">
                                <a href="{void(0)}"><img src="images/product-image-1.png" alt="image"></a>
                            </div>
                            <h4 class="price-item">$450.54</h4>
                            <h6><a href="{void(0)}">Winners Drawing In</a></h6>
                            <div class="countdown flex justify-center items-center">
                                <h6>
                                    <span class="days">00</span><span class="ref">D :</span>
                                </h6>
                                <h6>
                                    <span class="hours">00</span><span class="ref">H :</span>
                                </h6>
                                <h6>
                                    <span class="minutes">00</span><span class="ref">M :</span>
                                </h6>
                                <h6>
                                    <span class="seconds">00</span><span class="ref">S</span>
                                </h6>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6">
                        <div class="single-box">
                            <div class="img-area">
                                <a href="{void(0)}"><img src="images/product-image-2.png" alt="image"></a>
                            </div>
                            <h4 class="price-item">$450.54</h4>
                            <h6><a href="{void(0)}">Winners Drawing In</a></h6>
                            <div class="countdown flex justify-center items-center">
                                <h6>
                                    <span class="days">00</span><span class="ref">D :</span>
                                </h6>
                                <h6>
                                    <span class="hours">00</span><span class="ref">H :</span>
                                </h6>
                                <h6>
                                    <span class="minutes">00</span><span class="ref">M :</span>
                                </h6>
                                <h6>
                                    <span class="seconds">00</span><span class="ref">S</span>
                                </h6>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6">
                        <div class="single-box">
                            <div class="img-area">
                                <a href="{void(0)}"><img src="images/product-image-1.png" alt="image"></a>
                            </div>
                            <h4 class="price-item">$450.54</h4>
                            <h6><a href="{void(0)}">Winners Drawing In</a></h6>
                            <div class="countdown flex justify-center items-center">
                                <h6>
                                    <span class="days">00</span><span class="ref">D :</span>
                                </h6>
                                <h6>
                                    <span class="hours">00</span><span class="ref">H :</span>
                                </h6>
                                <h6>
                                    <span class="minutes">00</span><span class="ref">M :</span>
                                </h6>
                                <h6>
                                    <span class="seconds">00</span><span class="ref">S</span>
                                </h6>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Winners Drawing end -->

    <!-- Social Area start -->
    <section class="">
        <div class="overlay pb-120">
            <div class="container-fruid">
                <div class="social-area overflow-hidden">
                    <div class="row justify-center">
                        <div class="col-lg-10">
                            <div class="main-content">
                                <div class="row justify-center">
                                    <div class="col-lg-6 mt-80 mb-80 text-center">
                                        <div class="section-text">
                                            <div class="logo-area mb-4">
                                                <a href="dashboard.html">
                                                    <img src="images/logo-dark.png" class="logo" alt="logo">
                                                </a>
                                            </div>
                                            <p>Get Instant Access to Top Paying Surveys. Earn Up To $300 Per Day by Sharing your Opinion.If you want an easy way to make money from surveys, you should join the ugetpaid community.</p> 
                                        </div>
                                        <ul class="flex flex-wrap justify-center gap-2 ga-sm-3 social">
                                            <li><a href="{void(0)}"><i class="fab fa-facebook-f"></i></a></li>
                                            <li><a href="{void(0)}"><i class="fab fa-twitter"></i></a></li>
                                            <li><a href="{void(0)}"><i class="fab fa-instagram"></i></a></li>
                                            <li><a href="{void(0)}"><i class="fab fa-discord"></i></a></li>
                                            <li><a href="{void(0)}"><i class="fab fa-reddit-alien"></i></a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Social Area end -->
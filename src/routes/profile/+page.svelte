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
                            <h2>Profile</h2>
                            <div class="breadcrumb-area">
                                <nav aria-label="breadcrumb">
                                    <ol class="breadcrumb flex items-center">
                                        <li class="breadcrumb-item"><a href="dashboard.html">Home</a></li>
                                        <li class="breadcrumb-item active" aria-current="page">Profile</li>
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

    <!-- User Information start -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="user-info-popup information">
                    <div class="row mt-4">
                        <div class="col-xxl-6 col-lg-5 col-md-8">
                            <div class="main-content pb-0">
                                <div class="single-box">
                                    <div class="border-gradient mt-4 inline-flex justify-center">
                                        <div class="profile">
                                            <img src="images/winner-img-4.png" alt="image">
                                        </div>
                                    </div>
                                    <div class="profile-area flex gap-3 mt-4 mb-4 justify-center items-center">
                                        <div class="rank relative flex items-center justify-center">
                                            <img src="images/rank-bg.png" class="max-un" alt="image">
                                            <div class="abs-area absolute">
                                                <p class="mdtxt">28</p>
                                            </div>
                                        </div>
                                        <div class="text-area text-start">
                                            <h5>silverlion355</h5>
                                            <p class="mdtxt">User Id : 952033</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="single-box">
                                    <div class="progress-area">
                                        <div class="scale">
                                            <span class="mdtxt">2,870 XP Earned. 30 XP required for next level up.</span>
                                        </div>
                                        <div class="progress">
                                            <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-xxl-6 col-lg-7 col-md-10">
                            <div class="main-content">
                                <div class="row">
                                    <div class="col-sm-6 col-md-4">
                                        <div class="single-box">
                                            <h5>69</h5>
                                            <p class="mdtxt">Completed Offers</p>
                                        </div>
                                    </div>
                                    <div class="col-sm-6 col-md-4">
                                        <div class="single-box">
                                            <h5>29,216</h5>
                                            <p class="mdtxt">Coins Earned</p>
                                        </div>
                                    </div>
                                    <div class="col-sm-6 col-md-4">
                                        <div class="single-box">
                                            <h5>16</h5>
                                            <p class="mdtxt">Users Referred</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="chart-area">
                                    <div class="flex flex-wrap head-area items-center justify-between">
                                        <h5>Recent Earning</h5>
                                        <span class="mdtxt">- Last 7 days</span>
                                    </div>
                                    <div id="profile-chart"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-4 inform-area">
                        <div class="col-lg-12">
                            <div class="main-content">
                                <div class="row">
                                    <div class="col-lg-6">
                                        <div class="single-area">
                                            <h5 class="text-center">Your Info</h5>
                                            <ul>
                                                <li>
                                                    <span class="mdtxt">Ugetpaid ID</span>
                                                    <span class="lgtxt">6522146</span>
                                                </li>
                                                <li>
                                                    <span class="mdtxt">Balance</span>
                                                    <span class="lgtxt">4,000 Coins</span>
                                                </li>
                                                <li>
                                                    <span class="mdtxt">Referrer</span>
                                                    <span class="lgtxt">10</span>
                                                </li>
                                                <li>
                                                    <span class="mdtxt">Referral Earnings</span>
                                                    <span class="lgtxt">1,000</span>
                                                </li>
                                                <li>
                                                    <span class="mdtxt">Date Joined</span>
                                                    <span class="lgtxt">2022-09-30</span>
                                                </li>
                                                <li>
                                                    <span class="mdtxt">400</span>
                                                    <span class="lgtxt"><a href="../../cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="523120272812372a333f223e377c313d3f">[email&#160;protected]</a></span>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                    <div class="col-lg-6 mt-3 mt-lg-0">
                                        <div class="single-area">
                                            <h5 class="text-center">Setting</h5>
                                            <form action="profile.html#">
                                                <div class="single-item">
                                                    <div class="head-item">
                                                        <h5 class="mdtxt">Change Display Name</h5>
                                                    </div>
                                                    <div class="form-control">
                                                        <label class="mdtxt" for="name">Edit Display Name:</label>
                                                        <div class="input-area mt-2 flex items-center gap-3">
                                                            <input type="text" id="name" value="Namio321" placeholder="Enter new name...">    
                                                            <button class="cmn-btn">Change</button>
                                                        </div>
                                                        <p class="form-text">Maximum length: 40 characters</p>
                                                    </div>
                                                </div>
                                                <div class="single-item">
                                                    <div class="head-items">
                                                        <h5 class="mdtxt mb-1">Profile Visibility</h5>
                                                        <p class="mdtxt">Setting your profile to private will prevent anyone from viewing your public profile information except your username and avatar.</p>
                                                    </div>
                                                    <div class="radio-area flex flex-wrap justify-center">
                                                        <label class="single-radio">Public
                                                            <input type="radio" name="loan">
                                                            <span class="checkmark"></span>
                                                        </label>
                                                        <label class="single-radio">Private
                                                            <input type="radio" checked name="loan">
                                                            <span class="checkmark"></span>
                                                        </label>
                                                    </div>
                                                </div>
                                            </form>
                                        </div>
                                    </div>
                                    <div class="col-lg-12 mt-4">
                                        <div class="single-area">
                                            <h5>Referrals</h5>
                                            <p class="mdtxt">Share your referral link and earn 5% of all offers completed by your users - including name bonuses! Note: Referral bonus does not apply to video offers.Your referred users will also receive 100 coins as a welcome bonus.</p>
                                            <div class="affiliates-link mt-3">
                                                <p class="mdtxt">Refer users - get rewarded!</p>
                                                <div class="your-code">
                                                    <p>Your referral code : <span>7f66f48062</span></p>
                                                    <button class="cmn-btn">Copy link</button>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-4">
                        <div class="col-lg-12">
                            <div class="single-area">
                                <div class="delete-acc mt-3">
                                    <h5 class="m-1">Delete your Account</h5>
                                    <p class="mdtxt">consectetur adipiscing elit duis tristique sollicitudin nibh sit amet commodo nulla facilisi nullam vehicula ipsum a arcu cursus vitae congue</p>
                                    <div class="content-area mt-3">
                                        <h6 class="mdtxt mb-2">Delete Account</h6>
                                        <button class="cmn-btn">Delete Account</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- User Information end -->

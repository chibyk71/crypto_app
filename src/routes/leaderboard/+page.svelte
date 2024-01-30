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
                            <h2>Leaderboard</h2>
                            <div class="breadcrumb-area">
                                <nav aria-label="breadcrumb">
                                    <ol class="breadcrumb flex items-center">
                                        <li class="breadcrumb-item"><a href="dashboard.html">Home</a></li>
                                        <li class="breadcrumb-item active" aria-current="page">Leaderboard</li>
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

    <!-- Price Area Area start -->
    <section class=" paid-surveys">
        <div class="price-area mt-4 pt-80">
            <div class="container-fruid pb-120">
                <div class="row justify-center">
                    <div class="col-xxl-6 col-xl-8 col-md-10">
                        <div class="price-icon-area pb-80">
                            <div class="icon-area">
                                <img src="images/price-box-icon.png" class="max-un" alt="icon">
                            </div>
                            <div class="price flex flex-wrap items-center justify-center gap-3">
                                <p class="lgtxt">$500.00 Daily</p>
                                <p class="lgtxt">$10,000.00 Monthly</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Price Area Area end -->

    <!-- Leaderboard Section start -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="leaderboard-section pb-120">
                    <div class="row justify-center items-center">
                        <div class="col-xxl-5 col-lg-6 col-sm-10">
                            <div class="section-text text-center">
                                <h6 class="sub-title">Leaderboard</h6>
                                <h3 class="title">The top earners are rewarded once every week!</h3>
                                <p>Hard work pays off. Can you make it to the top? Note that the leaderboard updates every 10 minutes. Learn more about the leaderboard.</p>
                            </div>
                        </div>
                    </div>
                    <div class="row justify-center">
                        <div class="col-xxl-4 col-xl-6 col-md-6 text-center">
                            <ul class="nav inline-flex mb-5 justify-center gap-3" role="tablist">
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link cmn-btn active" id="choose-tab" data-bs-toggle="tab" data-bs-target="#choose" type="button"
                                        role="tab" aria-controls="choose" aria-selected="true">
                                        <span class="mdtxt">Daily</span>
                                    </button>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link cmn-btn" id="complete-tab" data-bs-toggle="tab" data-bs-target="#complete" type="button"
                                        role="tab" aria-controls="complete" aria-selected="false">
                                        <span class="mdtxt">Monthly</span>
                                    </button>
                                </li>
                            </ul>
                            <p class="mdtxt text-center">The current period ends in</p>
                            <div class="countdown flex justify-center items-center">
                                <h5>
                                    <span class="days">00</span><span class="ref">D :</span>
                                </h5>
                                <h5>
                                    <span class="hours">00</span><span class="ref">H :</span>
                                </h5>
                                <h5>
                                    <span class="minutes">00</span><span class="ref">M :</span>
                                </h5>
                                <h5>
                                    <span class="seconds">00</span><span class="ref">S</span>
                                </h5>
                            </div>
                        </div>
                    </div>
                    <!-- TODO do tab -->
                    <div class="tab-content mt-30">
                        <div class="tab-pane fade show active" id="choose" role="tabpanel" aria-labelledby="choose-tab">
                            <div class="row cus-mar">
                                <div class="col-xl-4 col-sm-6">
                                    <div class="single-box relative" data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                        <div class="abs-top">
                                            <p class="lgtxt">1st</p>
                                            <p class="mdtxt">Place</p>
                                        </div>
                                        <div class="border-gradient relative inline-flex justify-center">
                                            <div class="abs-area absolute">
                                                <img src="images/icon/crown-kings.png" alt="icon">
                                            </div>
                                            <div class="profile">
                                                <img src="images/winner-img-1.png" alt="image">
                                            </div>
                                        </div>
                                        <div class="info-area mt-4">
                                            <h5>crazyfish228</h5>
                                            <p class="mdtxt">696,445 Points</p>
                                        </div>
                                        <div class="coin-bonus mt-5 flex justify-between items-center">
                                            <div class="single">
                                                <p class="lgtxt">45,000</p>
                                                <p class="mdtxt">Coins</p>
                                            </div>
                                            <div class="single">
                                                <p class="lgtxt">+10,000</p>
                                                <p class="mdtxt">Bonus</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-xl-4 col-sm-6">
                                    <div class="single-box relative" data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                        <div class="abs-top">
                                            <p class="lgtxt">2nd</p>
                                            <p class="mdtxt">Place</p>
                                        </div>
                                        <div class="border-gradient relative inline-flex justify-center">
                                            <div class="abs-area absolute">
                                                <img src="images/icon/crown-kings.png" alt="icon">
                                            </div>
                                            <div class="profile">
                                                <img src="images/winner-img-2.png" alt="image">
                                            </div>
                                        </div>
                                        <div class="info-area mt-4">
                                            <h5>silverlion355</h5>
                                            <p class="mdtxt">696,445 Points</p>
                                        </div>
                                        <div class="coin-bonus mt-5 flex justify-between items-center">
                                            <div class="single">
                                                <p class="lgtxt">45,000</p>
                                                <p class="mdtxt">Coins</p>
                                            </div>
                                            <div class="single">
                                                <p class="lgtxt">+10,000</p>
                                                <p class="mdtxt">Bonus</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-xl-4 col-sm-6">
                                    <div class="single-box relative" data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                        <div class="abs-top">
                                            <p class="lgtxt">3rd</p>
                                            <p class="mdtxt">Place</p>
                                        </div>
                                        <div class="border-gradient relative inline-flex justify-center">
                                            <div class="abs-area absolute">
                                                <img src="images/icon/crown-kings.png" alt="icon">
                                            </div>
                                            <div class="profile">
                                                <img src="images/winner-img-3.png" alt="image">
                                            </div>
                                        </div>
                                        <div class="info-area mt-4">
                                            <h5>ticklishkoala607</h5>
                                            <p class="mdtxt">696,445 Points</p>
                                        </div>
                                        <div class="coin-bonus mt-5 flex justify-between items-center">
                                            <div class="single">
                                                <p class="lgtxt">45,000</p>
                                                <p class="mdtxt">Coins</p>
                                            </div>
                                            <div class="single">
                                                <p class="lgtxt">+10,000</p>
                                                <p class="mdtxt">Bonus</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="table-responsive">
                                <table class="table middle w-full">
                                    <tbody>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>04</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-1.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">whitegoose497</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>05</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-3.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">brownfish258</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>06</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-4.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">silverduck204</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>07</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-5.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">sadpanda176</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>08</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-6.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">whitefish664</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>09</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-7.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">whiteswan331</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                            <nav aria-label="Page navigation" class="flex justify-center mt-3 mt-md-0">
                                <ul class="pagination flex justify-center items-center">
                                    <li class="page-item">
                                        <a class="page-link previous" href="{void(0)}" aria-label="Previous">
                                            <i class="fa-solid fa-angles-left"></i>
                                        </a>
                                    </li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">01</a></li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">02</a></li>
                                    <li class="page-item"><a class="page-link active" href="{void(0)}">03</a></li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">04</a></li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">05</a></li>
                                    <li class="page-item">
                                        <a class="page-link next" href="{void(0)}" aria-label="Next">
                                            <i class="fa-solid fa-angles-right"></i>
                                        </a>
                                    </li>
                                </ul>
                            </nav>
                        </div>
                        <div class="tab-pane fade" id="complete" role="tabpanel" aria-labelledby="complete-tab">
                            <div class="row cus-mar">
                                <div class="col-xl-4 col-sm-6">
                                    <div class="single-box relative" data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                        <div class="abs-top">
                                            <p class="lgtxt">1st</p>
                                            <p class="mdtxt">Place</p>
                                        </div>
                                        <div class="border-gradient relative inline-flex justify-center">
                                            <div class="abs-area absolute">
                                                <img src="images/icon/crown-kings.png" alt="icon">
                                            </div>
                                            <div class="profile">
                                                <img src="images/winner-img-1.png" alt="image">
                                            </div>
                                        </div>
                                        <div class="info-area mt-4">
                                            <h5>crazyfish228</h5>
                                            <p class="mdtxt">696,445 Points</p>
                                        </div>
                                        <div class="coin-bonus mt-5 flex justify-between items-center">
                                            <div class="single">
                                                <p class="lgtxt">45,000</p>
                                                <p class="mdtxt">Coins</p>
                                            </div>
                                            <div class="single">
                                                <p class="lgtxt">+10,000</p>
                                                <p class="mdtxt">Bonus</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-xl-4 col-sm-6">
                                    <div class="single-box relative" data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                        <div class="abs-top">
                                            <p class="lgtxt">2nd</p>
                                            <p class="mdtxt">Place</p>
                                        </div>
                                        <div class="border-gradient relative inline-flex justify-center">
                                            <div class="abs-area absolute">
                                                <img src="images/icon/crown-kings.png" alt="icon">
                                            </div>
                                            <div class="profile">
                                                <img src="images/winner-img-2.png" alt="image">
                                            </div>
                                        </div>
                                        <div class="info-area mt-4">
                                            <h5>silverlion355</h5>
                                            <p class="mdtxt">696,445 Points</p>
                                        </div>
                                        <div class="coin-bonus mt-5 flex justify-between items-center">
                                            <div class="single">
                                                <p class="lgtxt">45,000</p>
                                                <p class="mdtxt">Coins</p>
                                            </div>
                                            <div class="single">
                                                <p class="lgtxt">+10,000</p>
                                                <p class="mdtxt">Bonus</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-xl-4 col-sm-6">
                                    <div class="single-box relative" data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                        <div class="abs-top">
                                            <p class="lgtxt">3rd</p>
                                            <p class="mdtxt">Place</p>
                                        </div>
                                        <div class="border-gradient relative inline-flex justify-center">
                                            <div class="abs-area absolute">
                                                <img src="images/icon/crown-kings.png" alt="icon">
                                            </div>
                                            <div class="profile">
                                                <img src="images/winner-img-3.png" alt="image">
                                            </div>
                                        </div>
                                        <div class="info-area mt-4">
                                            <h5>ticklishkoala607</h5>
                                            <p class="mdtxt">696,445 Points</p>
                                        </div>
                                        <div class="coin-bonus mt-5 flex justify-between items-center">
                                            <div class="single">
                                                <p class="lgtxt">45,000</p>
                                                <p class="mdtxt">Coins</p>
                                            </div>
                                            <div class="single">
                                                <p class="lgtxt">+10,000</p>
                                                <p class="mdtxt">Bonus</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="table-responsive">
                                <table class="table middle">
                                    <tbody>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>04</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-1.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">whitegoose497</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>05</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-3.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">brownfish258</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>06</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-4.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">silverduck204</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>07</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-5.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">sadpanda176</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>08</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-6.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">whitefish664</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                        <tr data-bs-toggle="modal" data-bs-target="#userInfoMod">
                                            <th class="border-left" scope="row">
                                                <span>09</span>
                                            </th>
                                            <td>
                                                <span class="img-area">
                                                    <img src="images/table-img-7.png" alt="icon">
                                                </span>
                                                <span class="lgtxt">whiteswan331</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">512,237</span>
                                                <span class="mdtxt">Points</span>
                                            </td>
                                            <td class="grid-area">
                                                <span class="mdtxt">79,200</span>
                                                <span class="mdtxt">Coins</span>
                                            </td>
                                            <td class="grid-area border-right">
                                                <span class="mdtxt">+15,000</span>
                                                <span class="mdtxt">Bonus</span>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                            <nav aria-label="Page navigation" class="flex justify-center mt-3 mt-md-0">
                                <ul class="pagination justify-center items-center">
                                    <li class="page-item">
                                        <a class="page-link previous" href="{void(0)}" aria-label="Previous">
                                            <i class="fa-solid fa-angles-left"></i>
                                        </a>
                                    </li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">01</a></li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">02</a></li>
                                    <li class="page-item"><a class="page-link active" href="{void(0)}">03</a></li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">04</a></li>
                                    <li class="page-item"><a class="page-link" href="{void(0)}">05</a></li>
                                    <li class="page-item">
                                        <a class="page-link next" href="{void(0)}" aria-label="Next">
                                            <i class="fa-solid fa-angles-right"></i>
                                        </a>
                                    </li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Leaderboard Section end -->

    <!-- User Information Popup start -->
    <!-- TODO modal -->
    <div class="user-info-popup cmn-popup hidden">
        <div class="container-fruid">
            <div class="row">
                <div class="col-xl-6">
                    <div class="modal fade" id="userInfoMod" aria-hidden="true" >
                        <div class="modal-dialog modal-dialog-centered relative">
                            <div class="modal-content">
                                <div class="modal-header justify-between absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="main-content text-center">
                                    <h6 class="text-start">User Information</h6>
                                    <div class="border-gradient mt-4 inline-flex justify-center">
                                        <div class="profile">
                                            <img src="images/winner-img-2.png" alt="image">
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
                                    <div class="progress-area">
                                        <div class="scale">
                                            <span class="mdtxt">2,870 XP Earned. 30 XP required for next level up.</span>
                                        </div>
                                        <div class="progress">
                                            <div class="progress-bar" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                        </div>
                                    </div>
                                    <div class="row mt-5">
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
                                        <div id="chart"></div>
                                    </div>
                                    <p class="mdtxt">Joined on 26/09/2022</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- User Information Popup start -->

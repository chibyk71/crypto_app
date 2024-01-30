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
                            <h2>Cashout</h2>
                            <div class="breadcrumb-area">
                                <nav aria-label="breadcrumb">
                                    <ol class="breadcrumb flex items-center">
                                        <li class="breadcrumb-item"><a href="dashboard.html">Home</a></li>
                                        <li class="breadcrumb-item active" aria-current="page">Cashout</li>
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

    <!-- Withdraw Area start -->
    <section class=" paid-surveys">
        <div class="withdraw-area mt-2">
            <div class="container-fruid pb-120">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="single-items">
                            <h4>Withdraw Cash</h4>
                            <div class="item-list cus-mar items-center gap-2">
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-1.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-20.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-19.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-18.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-17.png" alt="image">
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="single-items">
                            <h4>Withdraw Giftcards</h4>
                            <div class="item-list giftcards cus-mar flex-wrap items-center gap-2">
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-16.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-15.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-14.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-13.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-12.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-11.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-10.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-9.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-8.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-7.png" alt="image">
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="single-items">
                            <h4>Withdraw Skins</h4>
                            <div class="item-list cus-mar items-center gap-2">
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-6.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-5.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-4.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-3.png" alt="image">
                                    </button>
                                </div>
                                <div class="single-box">
                                    <button data-bs-toggle="modal" data-bs-target="#withdrawMod">
                                        <img src="images/payment-icon-2.png" alt="image">
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Withdraw Area end -->

    <!-- Withdraw Popup start -->
    <!-- TODO create modal -->
    <div class="withdraw-popup cmn-popup hidden">
        <div class="container-fruid">
            <div class="row">
                <div class="col-lg-6">
                    <div class="modal fade" id="withdrawMod" aria-hidden="true" >
                        <div class="modal-dialog modal-dialog-centered position-relative">
                            <div class="modal-content">
                                <div class="modal-header justify-between position-absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="main-content">
                                    <div class="head-area flex justify-between items-center">
                                        <div class="left-area grid gap-3">
                                            <div class="icon-area">
                                                <img src="images/icon/bitcoin-icon.png" class="max-un" alt="icon">
                                            </div>
                                            <p class="mdtxt">Crypto withdrawals take a few minutes to be sent. New users have to earn $2.00 in order to make their first withdrawal.</p>
                                        </div>
                                    </div>
                                    <div class="content-box">
                                        <form action="cashout.html#" id="form">
                                            <div class="input-box-area">
                                                <div class="form-control">
                                                    <label class="mdtxt" for="address">BTC Address</label>
                                                    <input type="text" id="address" placeholder="Enter your address...">
                                                    <p class="form-text">The Bitcoin Address for your Bitcoin Wallet.</p>
                                                </div>
                                                <div class="form-control">
                                                    <label class="mdtxt" for="amount">Amount</label>
                                                    <input type="number" id="amount" placeholder="Enter your amount...">
                                                    <p class="form-text">Minimum: 5,000 coins ($5.00).</p>
                                                </div>
                                            </div>
                                            <div class="info-area">
                                                <div class="single-box">
                                                    <p class="mdtxt">BTC Rate</p>
                                                    <h6>$19,165.41</h6>
                                                </div>
                                                <div class="single-box">
                                                    <p class="mdtxt">Fee</p>
                                                    <h6>441 Coins</h6>
                                                </div>
                                                <div class="single-box">
                                                    <p class="mdtxt">You’ll Receive</p>
                                                    <h6 class="highlight">00.00 BTC</h6>
                                                </div>
                                            </div>
                                            <div class="btn-area text-center">
                                                <button type="submit" class="cmn-btn w-100">Withdraw</button>
                                            </div>
                                        </form>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Withdraw Popup start -->

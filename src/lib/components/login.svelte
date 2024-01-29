    <!-- Login Registration start -->
    <div class="log-reg cmn-popup hidden">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <div class="modal fade" id="loginMod">
                        <div class="modal-dialog modal-dialog-centered">
                            <div class="modal-content">
                                <div class="modal-header justify-between absolute">
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"><i class="fa-solid fa-xmark"></i></button>
                                </div>
                                <div class="tab-content">
                                    <div class="tab-pane fade show active" id="loginArea" role="tabpanel" aria-labelledby="loginArea-tab">
                                        <div class="login-content">
                                            <div class="modal-header justify-center">
                                                <h4 class="title">Login to Ugetpaid</h4>
                                            </div>
                                            <div class="modal-body">
                                                <div class="form-area">
                                                    <form action="dashboard.html#">
                                                        <div class="row">
                                                            <div class="col-12">
                                                                <div class="form-control">
                                                                    <label class="mdtxt" for="email">Email*</label>
                                                                    <input type="text" id="email" placeholder="Enter your email">
                                                                </div>
                                                                <div class="form-control">
                                                                    <label class="mdtxt" for="password">Password*</label>
                                                                    <input type="text" id="password" placeholder="Enter your password">
                                                                </div>
                                                            </div>
                                                            <div class="col-12">
                                                                <div class="forget flex gap-2 flex-wrap items-center justify-between">
                                                                    <label class="checkbox-wrapper">Remember me
                                                                        <input type="checkbox" checked>
                                                                        <span class="checkmark"></span>
                                                                    </label>
                                                                    <a href="{void(0)}">Forgot Password?</a>
                                                                </div>
                                                            </div>
                                                            <div class="btn-area">
                                                                <a href="{void(0)}" class="cmn-btn">LOGIN</a>
                                                            </div>
                                                        </div>
                                                    </form>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="tab-pane fade" id="regArea" role="tabpanel" aria-labelledby="regArea-tab">
                                        <div class="reg-content regMod">
                                            <div class="modal-header justify-center">
                                                <div class="top-area text-center">
                                                    <h4 class="title">Welcome To Ugetpaid</h4>
                                                </div>
                                            </div>
                                            <div class="modal-body">
                                                <div class="form-area">
                                                    <form action="dashboard.html#">
                                                        <div class="row">
                                                            <div class="col-12">
                                                                <div class="form-control">
                                                                    <label class="mdtxt" for="regname">Name*</label>
                                                                    <input type="text" id="regname" placeholder="Enter your name">
                                                                </div>
                                                                <div class="form-control">
                                                                    <label class="mdtxt" for="regemail">Email*</label>
                                                                    <input type="text" id="regemail" placeholder="Enter your email">
                                                                </div>
                                                                <div class="form-control">
                                                                    <label class="mdtxt" for="regpassword">Password*</label>
                                                                    <input type="text" id="regpassword" placeholder="Enter your password">
                                                                </div>
                                                            </div>
                                                            <div class="btn-area">
                                                                <a href="{void(0)}" class="cmn-btn">Continue</a>
                                                            </div>
                                                        </div>
                                                    </form>
                                                    <div class="joining text-center">
                                                        <p>By joining I agree to receive emails</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <ul class="nav log-reg-btn justify-center">
                                    <li class="bottom-area" role="presentation">
                                        <button class="nav-link active" id="loginArea-tab" data-bs-toggle="tab" data-bs-target="#loginArea" type="button"
                                            role="tab" aria-controls="loginArea" aria-selected="true">
                                            Already a Member? <span>Login</span>
                                        </button>
                                    </li>
                                    <li class="bottom-area" role="presentation">
                                        <button class="nav-link" id="regArea-tab" data-bs-toggle="tab" data-bs-target="#regArea" type="button"
                                            role="tab" aria-controls="regArea" aria-selected="false">
                                            Not a member yet? <span>Register now</span>
                                        </button>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Login Registration end -->
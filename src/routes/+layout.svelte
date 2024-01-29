<script lang="ts">
	import { HelpingHand, HomeIcon, User2Icon, XIcon } from 'lucide-svelte';
	import "../grid.postcss"
	import '../app.postcss';
	import { BarsSolid } from 'svelte-awesome-icons';
	let sideBar = false
</script>
<div class="items-start w-screen row">
	<div class="sidebar-wrapper col-md-1" class:active={sideBar}>
        <a href={void(0)} class="close-btn" on:click={()=> sideBar = false}>
            <XIcon />
		</a>
        <div class="sidebar-logo">
            <a href="dashboard.html" class="flex items-center gap-2 mb-5">
                <img src="images/fav.png" alt="fav">
                <img src="images/logo.png" class="logo" alt="logo">
            </a>
        </div>
        <ul>
            <li class="active">
                <a href="dashboard.html">
                    <div class="icon-area">
                        <HomeIcon class="icon-j-home" />
                    </div>
                    <span>Home</span>
                </a>
            </li>
            <li>
                <a href="earn.html">
                    <div class="icon-area">
                        <i class="icon-e-earn" />
                    </div>
                    <span>Earn V1</span>
                </a>
            </li>
            <li>
                <a href="earn-points.html">
                    <div class="icon-area">
                        <i class="icon-e-earn" />
                    </div>
                    <span>Earn V2</span>
                </a>
            </li>
            <li>
                <a href="cashout.html">
                    <div class="icon-area">
                        <i class="icon-h-cashout" />
                    </div>
                    <span>Cashout</span>
                </a>
            </li>
            <li>
                <a href="leaderboard.html">
                    <div class="icon-area">
                        <i class="icon-k-leaderboard" />
                    </div>
                    <span>Leaderboard</span>
                </a>
                <span class="abs-item amount">$500 Daily</span>
            </li>
            <li>
                <a href="rewards.html">
                    <div class="icon-area">
                        <i class="icon-l-rewards" />
                    </div>
                    <span>Rewards</span>
                </a>
                <span class="abs-item">News</span>
            </li>
            <li>
                <a href="giveaway.html">
                    <div class="icon-area">
                        <i class="icon-g-giveaway" />
                    </div>
                    <span>Giveaway</span>
                </a>
            </li>
            <li>
                <a href="community.html">
                    <div class="icon-area">
                        <User2Icon class="icon-n-user" />
                    </div>
                    <span>Community</span>
                </a>
            </li>
            <li>
                <a href="support.html">
                    <div class="icon-area">
                        <HelpingHand class="icon-i-help" />
                    </div>
                    <span>Support</span>
                </a>
            </li>
        </ul>
    </div>
	<div class="{!sideBar?"col-md-11":"col-12"} px-4">
		<div class="navbar-area flex items-center justify-end sm:justify-between -mx-4">
			<a href="{void(0)}" class="sidebar-icon ml-2" on:click={()=>sideBar=true}>
				<BarsSolid class="fill-white" />
			</a>
			<form action="dashboard.html#" class="flex-1">
				<div class="form-group flex items-center">
					<i class="icon-m-search"></i>
					<input type="text" placeholder="Offername, Offer wall, event, giveaway">
				</div>
			</form>
			<div class="dashboard-nav">
				<div class="single-item flex gap-3">
					<button type="button" class="cmn-btn login" data-bs-toggle="modal" data-bs-target="#loginMod">
						<i class="fas fa-user"></i>
						Sign in
					</button>
					<button type="button" class="cmn-btn alt reg" data-bs-toggle="modal" data-bs-target="#loginMod">
						<i class="fas fa-user-plus"></i>
						Sign up
					</button>
				</div>
				<div class="single-item">
					<div class="chat-btn">
						<i class="icon-chat"></i>
					</div>
					<div class="chatbar-wrapper">
						<div class="close-btn">
							<i class="fa-solid fa-xmark"></i>
						</div>
						<div class="chat-area">
							<div class="chat-item">
								<div class="left-area">
									<div class="profile-area">
										<img src="images/profile-1.png" alt="image">
									</div>
									<div class="star-area flex items-center">
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
									</div>
								</div>
								<div class="right-area">
									<div class="title-area">
										<h6>Dave Fields</h6>
									</div>
									<div class="msg-wrap">
										<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
									</div>
								</div>
							</div>
							<div class="chat-item">
								<div class="left-area">
									<div class="profile-area">
										<img src="images/profile-2.png" alt="image">
									</div>
									<div class="star-area flex items-center">
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
									</div>
								</div>
								<div class="right-area">
									<div class="title-area">
										<h6>Reza Dave</h6>
									</div>
									<div class="msg-wrap">
										<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
									</div>
								</div>
							</div>
							<div class="chat-item">
								<div class="left-area">
									<div class="profile-area">
										<img src="images/profile-3.png" alt="image">
									</div>
									<div class="star-area flex items-center">
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
									</div>
								</div>
								<div class="right-area">
									<div class="title-area">
										<h6>Vincent Porter</h6>
									</div>
									<div class="msg-wrap">
										<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
									</div>
								</div>
							</div>
							<div class="chat-item">
								<div class="left-area">
									<div class="profile-area">
										<img src="images/profile-1.png" alt="image">
									</div>
									<div class="star-area flex items-center">
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
									</div>
								</div>
								<div class="right-area">
									<div class="title-area">
										<h6>Dave Fields</h6>
									</div>
									<div class="msg-wrap">
										<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
									</div>
								</div>
							</div>
							<div class="chat-item">
								<div class="left-area">
									<div class="profile-area">
										<img src="images/profile-2.png" alt="image">
									</div>
									<div class="star-area flex items-center">
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
										<a href="{void(0)}"><i class="fas fa-star"></i></a>
									</div>
								</div>
								<div class="right-area">
									<div class="title-area">
										<h6>Reza Dave</h6>
									</div>
									<div class="msg-wrap">
										<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
									</div>
								</div>
							</div>
						</div>
						<form class="send-form text-right text-end">
							<textarea cols="10" rows="4" placeholder="Type your message"></textarea>
							<button class="cmn-btn">Send</button>
						</form>
					</div>
				</div>
			</div>
		</div>
		
		<slot />
	</div>
</div>

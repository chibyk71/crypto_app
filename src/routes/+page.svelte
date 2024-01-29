<script lang="ts">
    import { createTabs,melt } from "@melt-ui/svelte";
	import Accordion from '$lib/components/accordion.svelte';
	import AccordionItem from '$lib/components/accordionItem.svelte';

    const {
        elements:{root,list,content,trigger},
        states:{value}
    } = createTabs({defaultValue:"choose",orientation:"vertical"})
    let tab = "choose";
</script>
    <!-- Latest Activites start -->
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

    <!-- Paid Surveys Section start -->
    <section class=" paid-surveys">
        <div class="overlay">
            <div class="container-fruid">
                <div class="get-paid overflow-hidden relative">
                    <div class="shape-area z-0">
                        <img src="images/get-paid-shape-1.png" class="shape-1" alt="shape">
                        <img src="images/get-paid-shape-2.png" class="shape-2" alt="shape">
                        <img src="images/get-paid-shape-3.png" class="shape-3" alt="shape">
                        <img src="images/get-paid-shape-4.png" class="shape-4" alt="shape">
                    </div>
                    <div class="row flex flex-wrap pt-120 pb-120">
                        <div class="col-xl-6 col-lg-7">
                            <div class="section-area">
                                <h1 class="grid">
                                    <span>Get Paid for</span>
                                    <span class="flex"><span class="typed"></span></span>
                                </h1>
                                <p class="xltxt">Get up to $7.5 for each survey,Safe and easy payment</p>
                                <a href="earn-points.html" class="cmn-btn">
                                    <img src="images/icon/btn-icon-1.png" alt="icon">
                                    Start Earning
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-6 lg:w-5/2 relative">
                            <div class="sec-img flex items-end absolute">
                                <img src="images/get-paid-illus.png" class="wow fadeInUp" alt="image">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Paid Surveys Section end -->

    <!-- Counter start -->
    <section class="">
        <div class="overlay pt-120 pb-120">
            <div class="container-fruid">
                <div class="counter-section overflow-hidden">
                    <div class="row cus-mar">
                        <div class="col-xl-4 col-sm-6 pr-4">
                            <div class="single-box border-gradient-second flex gap-3">
                                <div class="border-gradient">
                                    <img src="images/icon/counter-icon-1.png" alt="image">
                                </div>
                                <div class="title-area">
                                    <h5>0h 17m 16s</h5>
                                    <p class="mdtxt">Average time until user makes first cashout</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-xl-4 col-sm-6 pr-4">
                            <div class="single-box border-gradient-second flex gap-3">
                                <div class="border-gradient">
                                    <img src="images/icon/counter-icon-2.png" alt="image">
                                </div>
                                <div class="title-area">
                                    <h5>$9.19</h5>
                                    <p class="mdtxt">Average money earned by users yesterday</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-xl-4 col-sm-6 pr-4">
                            <div class="single-box border-gradient-second flex gap-3">
                                <div class="border-gradient">
                                    <img src="images/icon/counter-icon-3.png" alt="image">
                                </div>
                                <div class="title-area">
                                    <h5>$20,063,652</h5>
                                    <p class="mdtxt">Total USD earned on ugetpaid</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-xl-4 col-sm-6 pr-4">
                            <div class="single-box border-gradient-second flex gap-3">
                                <div class="border-gradient">
                                    <img src="images/icon/counter-icon-4.png" alt="image">
                                </div>
                                <div class="title-area">
                                    <h5>Total Members</h5>
                                    <p class="mdtxt">Average time until user makes first cashout</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Counter end -->

    <!-- How it works start -->
    <section class="">
        <div class="overlay pb-120">
            <div class="container-fruid">
                <div class="how-works pt-120 pb-120 overflow-hidden">
                    <div class="flex justify-between items-center" use:melt={$root}>
                        <div class="w-6/12">
                            <div class="section-text">
                                <h6 class="sub-title">Getting started is simple</h6>
                                <h3 class="title">How to Get Paid to Take Surveys</h3>
                                <p>It has been made as easy as possible to make money on ugetpaid.you can start in less than 30 seconds.</p>
                            </div>
                            <ul class="nav grid gap-4" use:melt={$list}>
                                <li class="nav-item">
                                    <button class="nav-link" class:active={$value==="choose"} use:melt={$trigger("choose")} type="button">
                                        <span class="xxltxt">01</span>
                                        <span class="xltxt">Choose a choose</span>
                                    </button>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link" class:active={$value==="complete"} use:melt={$trigger("complete")} type="button"
                                        role="tab" aria-controls="complete" aria-selected="false">
                                        <span class="xxltxt">02</span>
                                        <span class="xltxt">Complete the task</span>
                                    </button>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link" class:active={$value==="coins"} use:melt={$trigger("coins")} type="button"
                                        role="tab" aria-controls="coins" aria-selected="false">
                                        <span class="xxltxt">03</span>
                                        <span class="xltxt">Receive coins</span>
                                    </button>
                                </li>
                            </ul>
                        </div>
                        <div class="w-6/12">
                            <div class="tab-content">

                                <div class="tab-pane" use:melt={$content("choose")}>
                                    <span class="image-area">
                                        <img src="images/how-works-img-3.png" alt="icon">
                                    </span>
                                </div>
                                
                                <div class="tab-pane" use:melt={$content("complete")}>
                                    <span class="image-area">
                                        <img src="images/how-works-img-2.png" alt="icon">
                                    </span>
                                </div>
                            
                                <div class="tab-pane fade" use:melt={$content("coins")}>
                                    <span class="image-area">
                                        <img src="images/how-works-img-1.png" alt="icon">
                                    </span>
                                </div>
                                
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- How it works end -->

    <!-- ugetpaid profitable start -->
    <section class="">
        <div class="overlay pb-120">
            <div class="container-fruid">
                <div class="ugetpaid-profitable overflow-hidden">
                    <div class="row justify-center items-center">
                        <div class="col-xl-5 col-lg-7">
                            <div class="section-header text-center">
                                <h6 class="sub-title">Why is ugetpaid profitable</h6>
                                <h3 class="title">Be the First to Know About Top Paying Survey Opportunities</h3>
                                <p>Our Survey is so easy to use that a 16-year-old can start making a steady income online right away.</p>
                            </div>
                        </div>
                    </div>
                    <div class="row cus-mar items-center justify-center">
                        <div class="col-xxl-4 col-xl-5 col-lg-6 col-sm-8">
                            <div class="single-box grid-area">
                                <div class="image-area">
                                    <img src="images/profitable-illus-1.png" alt="image">
                                </div>
                                <div class="text-area">
                                    <div class="border-gradient">
                                        <img src="images/icon/profitable-icon-1.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <h5>Instant cashouts</h5>
                                        <p class="mdtxt">Nec sed enim vel dolor pellentesque feugiat scelerisque sodales. Risus morbi imperdiet mauris sit tempor. Quis nulla sed scelerisque ridiculus tellus massa quam.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-xxl-6 col-xl-7 col-lg-8 col-md-10">
                            <div class="single-box">
                                <div class="image-area">
                                    <img src="images/profitable-illus-2.png" alt="image">
                                </div>
                                <div class="text-area">
                                    <div class="border-gradient">
                                        <img src="images/icon/profitable-icon-2.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <h5>Instant cashouts</h5>
                                        <p class="mdtxt">Nec sed enim vel dolor pellentesque feugiat scelerisque sodales. Risus morbi imperdiet mauris sit tempor. Quis nulla sed scelerisque ridiculus tellus massa quam.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="single-box">
                                <div class="image-area">
                                    <img src="images/profitable-illus-3.png" alt="image">
                                </div>
                                <div class="text-area">
                                    <div class="border-gradient">
                                        <img src="images/icon/profitable-icon-3.png" alt="image">
                                    </div>
                                    <div class="title-area">
                                        <h5>Instant cashouts</h5>
                                        <p class="mdtxt">Nec sed enim vel dolor pellentesque feugiat scelerisque sodales. Risus morbi imperdiet mauris sit tempor. Quis nulla sed scelerisque ridiculus tellus massa quam.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- ugetpaid profitable end -->

    <!-- FAQs start -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="faqs-section pt-120 pb-120 overflow-hidden">
                    <div class="row justify-center items-center">
                        <div class="col-lg-6">
                            <div class="section-header text-center">
                                <h6 class="sub-title">FAQs</h6>
                                <h3 class="title">Frequently asked questions</h3>
                                <p>Frequently Asked Questions. Find below our most frequently asked or for more answers.</p>
                            </div>
                        </div>
                    </div>
                    <div class="flex justify-center">
                        <div class="col-xl-8">
                            <div class="faq-box">
                                <Accordion>
                                    <AccordionItem title="How to make money on ugetpaid?">
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                    </AccordionItem>
                                    <AccordionItem title="How is ugetpaid able to pay users?">
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                    </AccordionItem>
                                    <AccordionItem title="How long does it take to cash out your money?">
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                    </AccordionItem>
                                    <AccordionItem title="What are Terms and Conditions and Privacy Policy?">
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                    </AccordionItem>
                                    <AccordionItem title="How much money can you really earn on ugetpaid?">
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                    </AccordionItem>
                                    <AccordionItem title="What makes us unique?">
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cursus pulvinar egestas non convallis semper ut fermentum pellentesque accumsan. Tellus, vitae sapien ut nunc, consectetur risus vel. Ipsum ullamcorper nec ut tortor metus, euismod est, nunc. Morbi mi integer nam nullam tortor nisl quis at a. Duis viverra ac nunc amet sed. </p>
                                    </AccordionItem>
                                </Accordion>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- FAQs end -->

    <!-- Testimonial start -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="testimonials pt-120 pb-120 overflow-hidden">
                    <div class="row justify-center">
                        <div class="col-lg-6">
                            <div class="section-header text-center">
                                <h2 class="title">Our Client Say</h2>
                                <p>Backpacks in general fall into one of four categories: frameless, external frame, internal frame, and bodypack. A pack frame, when present, serves...</p>
                            </div>
                        </div>
                    </div>
                    <!-- TODO add carousel -->
                    <div class="testimonial-carousel">
                        <div class="single-content">
                            <div class="single-slide">
                                <div class="quotation-area absolute">
                                    <img src="images/icon/quotation.png" alt="image">
                                </div>
                                <div class="flex items-center">
                                    <div class="img-area">
                                        <img src="images/testimonial-1.png" alt="image">
                                    </div>
                                    <div class="designation text-start">
                                        <h6 class="lgtxt">John Doe</h6>
                                        <p class="mdtxt">Indonesia</p>
                                    </div>
                                </div>
                                <div class="main-body mt-4">
                                    <h5>“Great experience”</h5>
                                    <p class="description mt-2">Great experience. Nice. Excellent survey. Without any interruption we can do. Legit site .</p>
                                </div>
                                <div class="bottom-area flex items-baseline justify-between">
                                    <div class="star-area">
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                    </div>
                                    <p class="mdtxt">1 hour ago</p>
                                </div>
                            </div>
                        </div>
                        <div class="single-content">
                            <div class="single-slide">
                                <div class="quotation-area absolute">
                                    <img src="images/icon/quotation.png" alt="image">
                                </div>
                                <div class="flex items-center">
                                    <div class="img-area">
                                        <img src="images/testimonial-2.png" alt="image">
                                    </div>
                                    <div class="designation text-start">
                                        <h6 class="lgtxt">Alice Smith</h6>
                                        <p class="mdtxt">Vietnam</p>
                                    </div>
                                </div>
                                <div class="main-body mt-4">
                                    <h5>“Great experience”</h5>
                                    <p class="description mt-2">Great experience. Nice. Excellent survey. Without any interruption we can do. Legit site .</p>
                                </div>
                                <div class="bottom-area flex align-items-baseline justify-between">
                                    <div class="star-area">
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                    </div>
                                    <p class="mdtxt">1 hour ago</p>
                                </div>
                            </div>
                        </div>
                        <div class="single-content">
                            <div class="single-slide">
                                <div class="quotation-area absolute">
                                    <img src="images/icon/quotation.png" alt="image">
                                </div>
                                <div class="flex items-center">
                                    <div class="img-area">
                                        <img src="images/testimonial-3.png" alt="image">
                                    </div>
                                    <div class="designation text-start">
                                        <h6 class="lgtxt">Sophia Miller</h6>
                                        <p class="mdtxt">Canada</p>
                                    </div>
                                </div>
                                <div class="main-body mt-4">
                                    <h5>“Great experience”</h5>
                                    <p class="description mt-2">Great experience. Nice. Excellent survey. Without any interruption we can do. Legit site .</p>
                                </div>
                                <div class="bottom-area flex align-items-baseline justify-between">
                                    <div class="star-area">
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                    </div>
                                    <p class="mdtxt">1 hour ago</p>
                                </div>
                            </div>
                        </div>
                        <div class="single-content">
                            <div class="single-slide">
                                <div class="quotation-area absolute">
                                    <img src="images/icon/quotation.png" alt="image">
                                </div>
                                <div class="flex items-center">
                                    <div class="img-area">
                                        <img src="images/testimonial-4.png" alt="image">
                                    </div>
                                    <div class="designation text-start">
                                        <h6 class="lgtxt">John Doe</h6>
                                        <p class="mdtxt">Indonesia</p>
                                    </div>
                                </div>
                                <div class="main-body mt-4">
                                    <h5>“Great experience”</h5>
                                    <p class="description mt-2">Great experience. Nice. Excellent survey. Without any interruption we can do. Legit site .</p>
                                </div>
                                <div class="bottom-area flex align-items-baseline justify-between">
                                    <div class="star-area">
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                    </div>
                                    <p class="mdtxt">1 hour ago</p>
                                </div>
                            </div>
                        </div>
                        <div class="single-content">
                            <div class="single-slide">
                                <div class="quotation-area absolute">
                                    <img src="images/icon/quotation.png" alt="image">
                                </div>
                                <div class="flex items-center">
                                    <div class="img-area">
                                        <img src="images/testimonial-3.png" alt="image">
                                    </div>
                                    <div class="designation text-start">
                                        <h6 class="lgtxt">John Doe</h6>
                                        <p class="mdtxt">Indonesia</p>
                                    </div>
                                </div>
                                <div class="main-body mt-4">
                                    <h5>“Great experience”</h5>
                                    <p class="description mt-2">Great experience. Nice. Excellent survey. Without any interruption we can do. Legit site .</p>
                                </div>
                                <div class="bottom-area flex align-items-baseline justify-between">
                                    <div class="star-area">
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                        <a href="{void(0)}"><i class="fas fa-star"></i></a>
                                    </div>
                                    <p class="mdtxt">1 hour ago</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Testimonial end -->

    <!-- Call to action start -->
    <section class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="call-action pb-120 overflow-hidden">
                    <div class="row justify-center">
                        <div class="col-lg-10">
                            <div class="row justify-between">
                                <div class="col-xxl-7 col-xl-5 order-1 xl:order-none">
                                    <div class="sec-img [direction:rtl]">
                                        <img src="images/call-action-Illus.png" class="max-un" alt="image">
                                    </div>
                                </div>
                                <div class="col-xxl-5 col-xl-7">
                                    <div class="section-text">
                                        <h6 class="sub-title">What are you Waiting for?</h6>
                                        <h2 class="title">Start Earning Money Today</h2>
                                        <p>An average survey takes 10 minutes to complete and pays out $4, which equates to $24/hour.</p>
                                        <p>Getting paid to do surveys on the internet with ugetpaid is not only simple but also entertaining. Everyone who wants to join may do so without cost for their whole lives. On the internet, anybody can sign up and start making money right away at no cost.</p>
                                        <p>Participating in our online paid surveys does not need any prior expertise on your part in any way. We are just interested in hearing your completely honest opinion.</p>
                                    </div>
                                    <a href="earn-points.html" class="cmn-btn">
                                        <img src="images/icon/btn-icon-1.png" alt="icon">
                                        Start Earning Now
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Call to action end -->

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

    <!-- Footer Area Start -->
    <footer class="">
        <div class="overlay">
            <div class="container-fruid">
                <div class="footer-area overflow-hidden">
                    <div class="row mt-4 mb-4 gap-3 lg:gap-0 dark-sec justify-between items-center">
                        <div class="col-lg-7 lg:order-none order-1">
                            <div class="copyright text-lg-start text-center">
                                <p>Copyright © 2022 <a href="dashboard.html">UGETPAID</a>. All rights reserved.</p>
                            </div>
                        </div>
                        <div class="col-lg-5">
                            <ul class="flex flex-wrap gap-3 lg:justify-end justify-center">
                                <li><a href="support.html">Security</a></li>
                                <li><a href="terms-conditions.html">Terms</a></li>
                                <li><a href="privacy-policy.html">Privacy</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    <!-- Footer Area End -->
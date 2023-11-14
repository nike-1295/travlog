<template>
    <div>
        <section id="hero" class="container-fluid mt-5 pb-5">
            <div class="row">
                <div class="col-lg-5 mt-5 px-3 text-sm-left">
                    <button class="btn rounded-pill px-4 py-3 explore-btn">Explore the World!</button>
                    <h1 data-aos="fade-right" data-aos-once="true" class="display-3 mt-4 fw-bolder">
                        Travel <span class="top-destination-txt fw-bolder">top destination</span><br />of the world
                    </h1>
                    <p data-aos="fade-down" data-aos-once="true" data-aos-delay="300" class="text-secondary mt-5 w-85">
                        We always make sure our customers are happy by providing as many choices as possible
                    </p>
                    <div data-aos="fade-up" data-aos-once="true" data-aos-delay="600" class="mt-2">
                        <ul class="d-flex flex-row navbar-nav ml-auto pt-3">
                            <li class="nav-item px-lg-3">
                                <button
                                    class="btn btn-bg-purple text-white rounded-pill mx-lg-0 mx-md-2 mx-sm-2 px-4 py-2 mb-2 mb-lg-0">Get
                                    Started</button>
                            </li>
                            <li class="nav-item">
                                <button class="btn rounded-pill mx-lg-0 mx-md-2 mx-sm-2 px-4 py-2 border border-dark">Watch
                                    Demo</button>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="d-sm-none col-lg-7">
                    <div class="w-100">
                        <img data-aos="fade-up" data-aos-once="true" src="" class="mt-4" alt="" />
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'TopBanner',
}
</script>

<style scoped>
.w-85 {
    width: 85%;
}

.explore-btn {
    background-color: #f9f4f4fc;
    color: #fa408e;
}

.top-destination-txt {
    color: #fa559b;
}

.btn-bg-purple {
    background-color: #5d50c6;
}</style>
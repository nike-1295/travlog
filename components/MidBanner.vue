<template>
    <div class="container">
        <section class="container-fluid my-5">
            <div class="row">
                <div data-aos="fade-right" data-aos-delay="150" class="col-md-12 col-lg-6">
                    <div class="w-100">
                        <img src="" class="w-100" alt="" />
                    </div>
                </div>
                <div class="col-md-12 col-lg-6 px-4 px-sm-6 mt-5 display-6">
                    <h4 data-aos="fade-left" data-aos-delay="150" class="text-uppercase mb-3 mb-sm-2 travel-txt">Travel Point</h4>
                    <p data-aos="fade-right" data-aos-delay="300" class="mb-4 mb-sm-3 fw-bolder w-75">
                        We helping you find your dream location
                    </p>
                    <h5 data-aos="fade-down" data-aos-delay="150" class="d-sm-block text-secondary w-75">
                        Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC.
                    </h5>
                </div>
            </div>
        </section>
    </div>
</template>
  

<script>
import aosMixin from '@/mixins/aos'
export default {
    name: 'MidBanner',
    mixins: [aosMixin],
    data() {
        return {
        }
    },
}
</script>

<style scoped>
/* Optional: Add custom styles for the component */
.travel-txt {
    color: #fa559b;
    letter-spacing: 3px;
}
</style>

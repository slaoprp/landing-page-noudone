<template>
    <div class="hero-sass hero-swiper-btn" id="home">
        <div class="container_f1">
            <div class="swiper-wrapper">
                <swiper :options="swiperOption">
                    <div class="swiper-slide" :style="bgImg">
                        <div class="hero-item text-center">
                            <div class="hero-content">
                                <h2 class="h1 hero-content-title font-weight-light">Create powerful coaching flows</h2>
                                <h6 class="hero-content-subtitle">Anyone, anywhere, can be trained now</h6>
                                <!-- <router-link :to="{ path: 'branding' }" class="btn btn--green">
                                    <span class="btn-icon  ml-0 mr-2"><i class="fa fa-arrow-alt-to-bottom"></i></span> Get AeroLand
                                </router-link> -->
                            </div>
                            <div class="hero-thumb">
                                <img src="../assets/img/hero/hero-sass/sass-thumb-1.png" class="img-fluid" alt="hero thumb">
                            </div>
                        </div>
                    </div>
                </swiper>
            </div>
        </div>
    </div>

</template>

<script>
export default {
    data() {
        return {
            bgImg: {
                backgroundImage: `url(${require("../assets/img/bg/hero-background.jpeg")})`
            },
            swiperOption: {
                speed: 1500,
                loop: true,
                effect: 'fade',
                autoplay: false,
                spaceBetween : 30,
                navigation: {
                    nextEl: '.swiper-button-next',
                    prevEl: '.swiper-button-prev'
                },
            }
        };
    }
};
</script>

<style lang="scss" scoped>
    @import '../assets/scss/variabls.scss';
    @import '../assets/scss/elements/noudone.scss'
</style>

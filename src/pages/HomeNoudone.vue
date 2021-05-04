<template>
	<div class="main-container">
		<!-- Navbar section -->
		<HeaderNoudone />

		<!-- hero section -->
		<HeroNoudone class="hero-sass" />

    <TabCreate BgGradient="bg-gradient" id="create" />
		<!-- Gradation section start -->

		<!-- faq banner start -->
    <MobileExperience id="share" />

    <NoudoneFeature id="features" />

		<!-- footer section -->
    <FooterMain />

	</div>
</template>

<script>
	import HeaderNoudone from "../components/HeaderNoudone";
	import HeroNoudone from "../components/HeroNoudone";
	import Gradation from "../components/Gradation";
	import FaqBanner from "../components/FaqBanner";
	import CurveShape from "../components/CurveShape";
	import BannerOne from "../components/BannerOne";
	import NoudoneFeature from "../components/NoudoneFeature";
	import CtaOne from "../components/CtaOne";
	import FunFactOne from "../components/FunFactOne";
	import TestimonialTwo from "../components/TestimonialTwo";
	import BrandLogoCarousel from "../components/BrandLogoCarousel";
	import BannerBgOne from "../components/BannerBgOne";
	import FooterMain from "../components/FooterMain";
  import TabCreate from "../components/TabCreate";
  import MobileExperience from "../components/MobileExperience";
  import PricingOne from "../components/PricingOne";

	export default {
		name: "app",
		components: {
			HeaderNoudone,
			HeroNoudone,
			Gradation,
			CurveShape,
			FaqBanner,
			BannerOne,
			NoudoneFeature,
			CtaOne,
			FunFactOne,
			TestimonialTwo,
			BrandLogoCarousel,
			BannerBgOne,
			FooterMain,
      TabCreate,
      MobileExperience,
      PricingOne
		},

		metaInfo: {
            title: 'Noudone',
            htmlAttrs: {
                lang: 'en',
                amp: true
            }
        }
	};
</script>

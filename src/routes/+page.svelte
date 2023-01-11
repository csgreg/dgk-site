<script>
	import LatestWedding from '../components/latest-wedding/LatestWedding.svelte';
	import FestivalSection from '../components/festival-section/FestivalSection.svelte';
	import AboutUs from '../components/about-us/AboutUs.svelte';
	import Footer from '../components/footer/footer.svelte';
	import ReviewsSection from '../components/reviews-section/ReviewsSection.svelte';
	import FamilyGallery from '../components/family-gallery/FamilyGallery.svelte';
</script>

<svelte:head>
	<title>DGK Photography | Esküvői videó, film és képek készítése</title>
	<meta name="title" content="DGK Photography | Esküvői videó, film és képek készítése" />
	<meta
		name="description"
		content="Csodálatos és egyedi esküvői videót, filmet és képeket készítünk, amik évek múlva is örömöt okoznak. Drónfelvételeket, 4K felbontású videókat készítünk, melyből egy életre szóló filmet vágunk."
	/>
	<meta property="og:title" content="DGK Photography | Esküvői videó, film és képek készítése" />
	<meta
		property="og:description"
		content="Csodálatos és egyedi esküvői videót, filmet és képeket készítünk, amik évek múlva is örömöt okoznak. Drónfelvételeket, 4K felbontású videókat készítünk, melyből egy életre szóló filmet vágunk."
	/>
	<meta property="og:url" content="https://www.photographydgk.hu/" />
	<meta name="robots" content="index, follow" />
</svelte:head>

<section class="hero is-medium is-link main-hero">
	<div class="hero-body">
		<h1 class="title">DGK</h1>
		<h2 class="subtitle">Fényképezés, filmkészítés</h2>
	</div>
</section>
<LatestWedding />
<AboutUs />
<FestivalSection />
<FamilyGallery />
<ReviewsSection />
<Footer />

<style>
	.main-hero {
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/thumb.jpeg');
		background-size: cover;
		background-position: 50% 0;
		background-repeat: no-repeat;
		display: flex;
		height: 50vh;
		align-items: center;
		justify-content: center;
	}

	.title {
		font-weight: 300;
	}

	.subtitle {
		font-weight: 800;
	}

	.hero-body {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>

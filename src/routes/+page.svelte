<script>
	import LatestWedding from '../components/latest-wedding/LatestWedding.svelte';
	import FestivalSection from '../components/festival-section/FestivalSection.svelte';
	import AboutUs from '../components/about-us/AboutUs.svelte';
	import Footer from '../components/footer/footer.svelte';
	import ReviewsSection from '../components/reviews-section/ReviewsSection.svelte';
	import FamilyGallery from '../components/family-gallery/FamilyGallery.svelte';
	import PetchySection from '../components/petchy-section/PetchySection.svelte';
</script>

<svelte:head>
	<title>DGK Photography - Egyedi Esküvői Fotók és Filmek</title>
	<meta name="title" content="DGK Photography - Egyedi Esküvői Fotók és Filmek" />
	<meta
		name="description"
		content="Üdvözöljük a DGK Photography weboldalán! Fedezze fel profi esküvői fotóinkat és filmjeinket. Készítsünk egyedi felvételeket együtt!"
	/>
	<meta property="og:title" content="DGK Photography - Egyedi Esküvői Fotók és Filmek" />
	<meta
		property="og:description"
		content="Üdvözöljük a DGK Photography weboldalán! Fedezze fel profi esküvői fotóinkat és filmjeinket. Készítsünk egyedi felvételeket együtt!"
	/>
	<meta property="og:url" content="https://www.photographydgk.hu/" />
	<meta name="robots" content="index, follow" />
	<script
		src="https://static.elfsight.com/platform/platform.js"
		data-use-service-core
		defer
	></script>
</svelte:head>

<section class="hero is-medium main-hero">
	<div class="hero-body">
		<h1 class="title">DGK productions</h1>
		<h2 class="subtitle">Wedding photography and filmmaking</h2>
	</div>
</section>
<LatestWedding />
<FamilyGallery />
<AboutUs />
<div class="elfsight-app-70870fab-47fc-44d2-86ce-c114220715cd" />
<FestivalSection />
<ReviewsSection />
<PetchySection />
<Footer />

<style>
	.main-hero {
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/thumb.jpeg');
		background-size: cover;
		background-position: 10% 45%;
		background-repeat: no-repeat;
		display: flex;
		height: 50vh;
		align-items: center;
		justify-content: center;
	}

	.title {
		margin-top: 24px;
		font-weight: 300;
		color: white;
	}

	.subtitle {
		font-weight: 300;
		color: white;
	}

	@media screen and (max-width: 800px) {
		.main-hero {
			background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/thumbnail.JPG');
			background-position: 0 70%;
		}

		.title {
			margin-top: 24px;
			font-weight: 100;
			color: white;
		}

		.subtitle {
			font-weight: 200;
			color: white;
		}
	}

	.hero-body {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>

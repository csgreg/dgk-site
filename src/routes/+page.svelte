<script>
	import LatestWedding from '../components/latest-wedding/LatestWedding.svelte';
	import FestivalSection from '../components/festival-section/FestivalSection.svelte';
	import AboutUs from '../components/about-us/AboutUs.svelte';
	import Footer from '../components/footer/footer.svelte';
</script>

<section class="hero is-medium is-link main-hero">
	<div class="hero-body">
		<h1 class="title">DGK</h1>
		<h2 class="subtitle">Fényképezés, filmkészítés</h2>
	</div>
</section>
<LatestWedding />
<AboutUs />
<FestivalSection />
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

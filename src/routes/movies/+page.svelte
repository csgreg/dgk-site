<script>
	import Footer from '../../components/footer/footer.svelte';
</script>

<svelte:head>
	<title>DGK Photography | Esküvői filmek</title>
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
	<meta property="og:url" content="https://www.photographydgk.hu/movies" />
	<meta name="robots" content="index, follow" />
</svelte:head>

<div class="movies-page">
	<h1 class="movies-title">Legutóbbi esküvői filmjeink</h1>
	<div class="container">
		<div class="columns">
			<div class="column video-column">
				<div>
					<iframe
						title="Virág és Norbi esküvői filmje"
						class="video"
						src="https://www.youtube.com/embed/hP7dpHYA0xM"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
					/>
				</div>
				<div>
					<iframe
						title="Rebeka és Tibi esküvői filmje"
						class="video"
						src="https://www.youtube.com/embed/8gVgtzZqHiM"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
					/>
				</div>
				<div>
					<iframe
						title="Mariann és Zsolt esküvői filmje"
						class="video"
						src="https://www.youtube.com/embed/KUSvo194VRk"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
					/>
				</div>
			</div>
			<div class="column video-column">
				<div>
					<iframe
						title="Ági és Attila esküvői videója"
						class="video"
						src="https://www.youtube.com/embed/gzHG49Zg62k"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
					/>
				</div>
				<div>
					<iframe
						title="Brigi és Zoli esküvői filmje"
						class="video"
						src="https://www.youtube.com/embed/Qm1YDuvhkSY"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
					/>
				</div>
				<div>
					<iframe
						title="Erika és Sándor esküvői filmje"
						class="video"
						src="https://www.youtube.com/embed/xWGv2ij6JOA"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
					/>
				</div>
			</div>
		</div>
	</div>
</div>
<Footer />

<style>
	.movies-page {
		display: flex;
		align-items: center;
		flex-direction: column;
	}

	.movies-title {
		font-size: 24px;
		font-weight: 600;
		margin: 32px 0 12px;
	}

	.video {
		padding: 12px;
		aspect-ratio: 16 / 9;
		width: 500px;
		max-width: 100%;
	}

	.video-column:first-of-type {
		display: flex;
		flex-direction: column;
		align-items: end;
	}

	.video-column:last-of-type {
		display: flex;
		flex-direction: column;
		align-items: start;
	}

	@media only screen and (max-width: 769px) {
		.video-column {
			justify-content: center !important;
		}
	}
</style>

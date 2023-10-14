<script>
	// @ts-ignore
	const handleCoverClick = (e, videoId) => {
		e.target.style.display = 'none';
		const video = document.querySelector(`#${videoId}`);
		if (video) {
			// @ts-ignore
			let videoSrc = video.src;
			videoSrc += '?autoplay=1';
			// @ts-ignore
			video.src = videoSrc;
		}
	};
</script>

<section class="festival-section">
	<div class="hero is-medium is-link festival-hero" />
	<div class="container festival-content">
		<h3 class="festival-title">Fesztivál és rendezvény filmezés</h3>
		<p class="festival-text">
			Az esküvői felkéréseink mellett ’23 nyarán már harmadjára keresett meg minket a Street Food
			Fesztivál főszervezője a Gyömrői, illetve az Alföldi Street Food Fesztivál aftermovie-jának
			elkészítésével kapcsolatban és mi az előző évek pozitív tapasztalatokkal felfegyverkezve ismét
			nagy örömmel vetettük bele magunkat a fesztivál filmkészítés világába. A mai napig úgy
			érezzük, hogy egy életre szóló élményben lehetett részünk ezeken a fesztiválokon, amit jövő
			nyáron újra átélhetünk!
		</p>
		<div class="video-container">
			<iframe
				class="video"
				src="https://www.youtube.com/embed/QEdYceK38tY"
				allow="accelerometer; autoplay; encrypted-media; gyroscope;"
				allowfullscreen
				title="Ceglédi Street Food fesztivál"
				id="video-fest"
			/>
			<div class="cover" on:click={(e) => handleCoverClick(e, 'video-fest')} />
		</div>
		<a data-sveltekit-reload class="button is-rounded more-movies-btn" href="/movies"
			>További filmek</a
		>
	</div>
</section>

<style>
	.festival-hero {
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/festival_thumbnail.webp');
		background-size: cover;
		background-position: 50% 70%;
		background-repeat: no-repeat;
		display: flex;
		height: 45vh;
		align-items: center;
		justify-content: center;
	}

	.festival-title {
		font-size: 24px;
		font-weight: 300;
		margin-bottom: 22px;
		margin-top: 24px;
		text-align: center;
	}

	.festival-text {
		max-width: 700px;
		margin: 0 12px 16px;
		text-align: center;
	}

	.festival-content {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}

	.video-container {
		width: 600px;
		max-width: 90%;
		position: relative;
		aspect-ratio: 16 / 9;
		max-width: 100%;
		height: auto;
	}

	.cover {
		position: absolute;
		top: 0;
		height: 100%;
		width: 100%;
		cursor: pointer;
		box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/video_covers/festivelcover.jpg');
		background-repeat: no-repeat, no-repeat;
		background-size: cover;
	}

	.video {
		width: 100%;
		height: 100%;
	}

	.more-movies-btn {
		margin: 12px;
		margin-bottom: 32px;
	}
</style>

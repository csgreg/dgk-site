<script>
	// @ts-ignore
	const handleCoverClick = (e, videoId) => {
		e.target.style.display = 'none';
		const video = document.querySelector(`#${videoId}`);
		if (video) {
			// @ts-ignore
			let videoSrc = video.src;
			videoSrc += '&autoplay=1';
			// @ts-ignore
			video.src = videoSrc;
			video.click();
		}
	};
</script>

<section>
	<div class="container last-wedding-movie-section">
		<h3 class="last-wedding-movie-title">Esküvői filmek</h3>
		<div class="columns">
			<div class="column">
				<div class="video-with-cover">
					<iframe
						title="Cinti és Sanyi előzetes rövid esküvői videója"
						class="video"
						src="https://www.youtube.com/embed/Li2zyCljKJo?modestbranding=1"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
						id="video-home-1"
					/>
					<div class="cover cover1" on:click={(e) => handleCoverClick(e, 'video-home-1')} />
				</div>
			</div>
			<div class="column">
				<div class="video-with-cover">
					<iframe
						title="Eszter és Tibi esküvői előzetes filmje"
						class="video"
						src="https://www.youtube.com/embed/0D6wnrg_AG0?modestbranding=1"
						allow="accelerometer; autoplay; encrypted-media; gyroscope;"
						allowfullscreen
						id="video-home-2"
					/>
					<div class="cover cover2" on:click={(e) => handleCoverClick(e, 'video-home-2')} />
				</div>
			</div>
		</div>
		<a data-sveltekit-reload class="button is-rounded more-movie-btn" href="/movies"
			>Nézd meg a többi filmünket is!</a
		>
	</div>
</section>

<style>
	.last-wedding-movie-section {
		display: flex;
		flex-direction: column;
		align-items: center;
		margin-top: 24px;
	}

	.last-wedding-movie-title {
		font-size: 24px;
		font-weight: 300;
		margin-bottom: 22px;
	}

	.cover1 {
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/video_covers/cintiandsanyi.jpeg');
		background-repeat: no-repeat, no-repeat;
		background-size: cover;
	}

	.cover2 {
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/video_covers/eszterandtibi.jpeg');
		background-repeat: no-repeat, no-repeat;
		background-size: cover;
	}

	.video-container {
		width: 600px;
		max-width: 90%;
	}

	.video-with-cover {
		position: relative;
		aspect-ratio: 16 / 9;
		/* width: 500px; */
		max-width: 100%;
	}

	@media screen and (min-width: 800px) {
		.video-with-cover {
			width: 500px;
		}
	}

	.cover {
		position: absolute;
		top: 0;
		height: 100%;
		width: 100%;
		cursor: pointer;
		border-radius: 5px;
		box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
	}

	.video {
		width: 100%;
		height: 100%;
	}

	.video:first-of-type {
		padding-left: 12px;
	}

	.video:last-of-type {
		padding-right: 12px;
	}

	.more-movie-btn {
		margin-bottom: 32px;
	}

	.divider {
		width: 90%;
		margin: auto;
		margin-top: 4px;
		margin-bottom: 4px;
	}
</style>

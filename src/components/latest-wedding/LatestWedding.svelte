<section>
	<div class="container last-wedding-movie-section">
		<h3 class="last-wedding-movie-title">Láttad már a legutóbbi filmejeinket?</h3>
		<div class="columns">
			<div class="column">
				<iframe
					class="video"
					src="https://www.youtube.com/embed/hP7dpHYA0xM"
					allow="accelerometer; autoplay; encrypted-media; gyroscope;"
					allowfullscreen
				/>
			</div>
			<div class="column">
				<iframe
					class="video"
					src="https://www.youtube.com/embed/gzHG49Zg62k"
					allow="accelerometer; autoplay; encrypted-media; gyroscope;"
					allowfullscreen
				/>
			</div>
		</div>
		<div class="video-container" />
		<a class="button is-rounded more-movie-btn" href="/movies">Nézd meg a többi filmünket is!</a>
	</div>
	<hr class="divider" />
</section>

<style>
	.last-wedding-movie-section {
		display: flex;
		flex-direction: column;
		align-items: center;
		margin-top: 24px;
	}

	.last-wedding-movie-title {
		font-size: 18px;
		font-weight: 700;
		margin-bottom: 12px;
	}

	.last-wedding-movie-text {
		margin: 8px 12px;
		text-align: center;
		max-width: 700px;
	}

	.video-container {
		width: 600px;
		max-width: 90%;
	}

	.video {
		aspect-ratio: 16 / 9;
		width: 100%;
	}

	.more-movie-btn {
		margin-bottom: 32px;
	}

	.divider {
		width: 90%;
		margin: auto;
		margin-top: 12px;
		margin-bottom: 12px;
	}
</style>

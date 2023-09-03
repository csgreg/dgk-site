<section>
	<div class="container last-wedding-movie-section">
		<h3 class="last-wedding-movie-title">Esküvői filmek</h3>
		<div class="columns">
			<div class="column">
				<iframe
					title="Cinti és Sanyi előzetes rövid esküvői videója"
					class="video"
					src="https://www.youtube.com/embed/Li2zyCljKJo"
					allow="accelerometer; autoplay; encrypted-media; gyroscope;"
					allowfullscreen
				/>
			</div>
			<div class="column">
				<iframe
					title="Ági és Attila esküvői videója"
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
		margin-bottom: 16px;
	}

	.video-container {
		width: 600px;
		max-width: 90%;
	}

	.video {
		aspect-ratio: 16 / 9;
		width: 500px;
		max-width: 100%;
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

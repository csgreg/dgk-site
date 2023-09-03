<section class="about-us">
	<div class="container about-us-section">
		<h3 class="about-us-title">Rólunk</h3>
		<div class="about-us-text">
			Az elmúlt 5 évben már több tucat esküvőn vettünk részt, elkészítettünk több tízezer képet,
			felvettünk több ezer snittet és izgatottan várjuk az elkövetkezendő évek újabb kihívásait.
		</div>
		<div class="about-us-cards columns">
			<div class="card column about-us-card">
				<div class="card-image">
					<figure class="image">
						<img
							loading="lazy"
							class="card-image"
							src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/about-lilian-new.jpeg"
							alt="Fénykép Liliről a színpad mellett"
						/>
					</figure>
				</div>
				<div class="card-content">
					<div class="media">
						<div class="media-content">
							<p class="title is-4">Lilian</p>
							<p class="subtitle is-6">@liliaan_k</p>
						</div>
					</div>
				</div>
			</div>
			<div class="card column about-us-card">
				<div class="card-image">
					<figure class="image">
						<img
							loading="lazy"
							class="card-image"
							src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/about-gergo-new.jpeg"
							alt="Fénykép Gergőről a színpadon"
						/>
					</figure>
				</div>
				<div class="card-content">
					<div class="media">
						<div class="media-content">
							<p class="title is-4">Gergő</p>
							<p class="subtitle is-6">@_csgrg_</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<a data-sveltekit-reload class="button is-rounded about-more-btn" href="/about"
			>Tudj meg többet rólunk</a
		>
	</div>
</section>

<style>
	.about-us-section {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.about-us-card {
		max-width: 350px;
		margin: 16px 8px;
		min-width: 300px;
	}

	.card-image {
		height: 217px !important;
		width: 326px !important;
	}

	.about-more-btn {
		margin-bottom: 32px;
	}

	.about-us-title {
		margin-top: 16px;
		margin-bottom: 16px;
		font-size: 18px;
		font-weight: 700;
	}

	.about-us-text {
		margin: 0 12px;
		text-align: center;
		max-width: 700px;
		margin-bottom: 12px;
	}

	.subtitle {
		display: flex;
		gap: 4px;
		align-items: center;
	}
</style>

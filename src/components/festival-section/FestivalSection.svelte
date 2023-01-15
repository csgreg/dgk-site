<section class="festival-section">
	<div class="hero is-medium is-link festival-hero" />
	<div class="container festival-content">
		<h3 class="festival-title">Fesztivál és rendezvény filmezés</h3>
		<p class="festival-text">
			Az esküvői felkéréseink mellett ’22 nyarán már másodjára keresett meg minket a Street Food
			Fesztivál főszervezője a Gyömrői, illetve az Alföldi Street Food Fesztivál aftermovie-jának
			elkészítésével kapcsolatban és mi az előző évi pozitív tapasztalatokkal felfegyverkezve ismét
			nagy örömmel vetettük bele magunkat a fesztivál filmkészítés világába. A mai napig úgy
			érezzük, hogy egy életre szóló élményben lehetett részünk ezeken a fesztiválokon, amit idén
			nyáron újra átélhetünk!
		</p>
		<div class="video-container">
			<iframe
				class="video"
				src="https://www.youtube.com/embed/QEdYceK38tY"
				allow="accelerometer; autoplay; encrypted-media; gyroscope;"
				allowfullscreen
				title="Ceglédi Street Food fesztivál"
			/>
		</div>
		<a class="button is-rounded more-movies-btn" href="/movies">További filmek</a>
	</div>
</section>

<style>
	.festival-hero {
		background-image: url('https://dgk-site-storage.s3.eu-central-1.amazonaws.com/fest.jpg');
		background-size: cover;
		background-position: 50% 70%;
		background-repeat: no-repeat;
		display: flex;
		height: 45vh;
		align-items: center;
		justify-content: center;
	}

	.festival-title {
		font-size: 18px;
		font-weight: 700;
		margin-bottom: 16px;
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
	}

	.video {
		aspect-ratio: 16 / 9;
		width: 100%;
	}

	.more-movies-btn {
		margin: 12px;
		margin-bottom: 32px;
	}
</style>

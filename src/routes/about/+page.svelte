<svelte:head>
	<title>Rólunk | DGK Photography - Egyedi Esküvői Fotók és Filmek Készítői</title>
	<meta name="title" content="Rólunk | DGK Photography - Egyedi Esküvői Fotók és Filmek Készítői" />
	<meta
		name="description"
		content=" Ismerje meg DGK Photography-t, és találkozzon azokkal az emberekkel, akik nagy lelkesedéssel készítik az esküvői fotókat és filmeket. Tudjon meg többet rólunk és szenvedélyünkről, a pillanatok megörökítéséről."
	/>
	<meta
		property="og:title"
		content="Rólunk | DGK Photography - Egyedi Esküvői Fotók és Filmek Készítői"
	/>
	<meta
		property="og:description"
		content=" Ismerje meg DGK Photography-t, és találkozzon azokkal az emberekkel, akik nagy lelkesedéssel készítik az esküvői fotókat és filmeket. Tudjon meg többet rólunk és szenvedélyünkről, a pillanatok megörökítéséről."
	/>
	<meta property="og:url" content="https://www.photographydgk.hu/about" />
	<meta name="robots" content="index, follow" />
</svelte:head>

<main class="about-us-page">
	<h1 class="about-us-title">Rólunk</h1>
	<div class="container about-us-container">
		<article class="message is-dark about-us-content">
			<div class="message-body">
				Amióta az eszünket tudjuk imádunk fotózni. Pályafutásunkat kezdetben külön, majd
				megismerkedésünk után együtt folytattuk főleg műtermi és szabadtéri fotózásokon, valamint
				rövid ’travel filmek’ készítésével. Így 2017-ben teljesen váratlanul ért minket, amikor egy
				ismerősünk felkért minket, hogy örökítsük meg a nagy napjukat fotó és kis film formájában.
				Ezt követően teljesen beszippantott minket az esküvői fotó-, és filmkészítés világa. Szájról
				szájra terjedve mára már több tucat szebbnél szebb esküvőn vettünk részt és élhettük ki a
				kreativitásunkat egy-egy film elkészítése során. A felszerelésünk és a tudásunk folyamatos
				fejlesztésével és bővítésével igyekszünk a lehető legjobb formánkat nyújtani az esküvőinken.
				Az utóbbi években a fesztivál film készítés világába is belecsöppentünk, ami végül a vártnál
				sokkal jobban a szívünkhöz nőtt. Idén nyáron zsinórban harmadjára ér minket az a
				megtiszteltetés, hogy mi készíthetjük el mind az Alföldi, mind pedig a Gyömrői Street Food
				Fesztivál aftermovieját.
			</div>
		</article>
		<div class="card about-card">
			<div class="card-image">
				<figure class="image is-3by3">
					<img
						loading="lazy"
						alt="TODO"
						class="about-image"
						src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/IMG-6987-min-min.jpg"
					/>
				</figure>
			</div>
		</div>
	</div>
</main>

<style>
	.about-us-page {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.about-us-container {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.about-us-title {
		font-size: 24px;
		margin-top: 40px;
		font-weight: 600;
	}

	.about-us-content {
		margin: 16px 12px 16px 24px;
		max-width: 800px;
	}

	.about-image {
		max-width: 300px;
		min-width: 300px;
	}

	.about-card {
		margin: 24px;
	}

	@media only screen and (min-width: 1000px) {
		.about-us-container {
			flex-direction: row;
		}
	}
</style>

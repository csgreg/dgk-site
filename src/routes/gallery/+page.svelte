<script>
	import Footer from '../../components/footer/footer.svelte';

	const gallery = {
		one: ['-1', '4', '8', '12', '16', '19', '20', '25', '33', '34', '38', '45', '49'],
		two: ['-2', '2', '5', '9', '13', '17', '21', '24', '26', '30', '35', '39', '42', '46', '50'],
		three: ['1', '6', '10', '14', '22', '27', '31', '36', '40', '43', '47', '51'],
		four: ['3', '7', '11', '15', '18', '23', '28', '29', '32', '37', '41', '48', '52', '53']
	};
</script>

<svelte:head>
	<title>DGK Photography | Galéria</title>
	<meta name="title" content="Esküvői Fotók és Filmek Galériája | DGK Photography" />
	<meta
		name="description"
		content="Nézze meg esküvői fotóink gyönyörű galériáját. Fedezze fel, hogyan örökítjük meg a pillanatokat művészi megközelítéssel!"
	/>
	<meta property="og:title" content="Esküvői Fotók és Filmek Galériája | DGK Photography" />
	<meta
		property="og:description"
		content="Nézze meg esküvői fotóink gyönyörű galériáját. Fedezze fel, hogyan örökítjük meg a pillanatokat művészi megközelítéssel!"
	/>
	<meta property="og:url" content="https://www.photographydgk.hu/gallery" />
	<meta name="robots" content="index, follow" />
</svelte:head>

<div class="gallery">
	<div class="container">
		<h1 class="gallery-title">Galéria</h1>
		<div class="rowc">
			<div class="columnc">
				{#each gallery.one as src}
					<img
						loading="lazy"
						alt="esküvői kreatív fénykép"
						src={`https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/${src}.jpg`}
						style="width: 100%"
					/>
				{/each}
			</div>
			<div class="columnc">
				{#each gallery.two as src}
					<img
						loading="lazy"
						alt="esküvői kreatív fénykép"
						src={`https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/${src}.jpg`}
						style="width: 100%"
					/>
				{/each}
			</div>
			<div class="columnc">
				{#each gallery.three as src}
					<img
						loading="lazy"
						alt="esküvői kreatív fénykép"
						src={`https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/${src}.jpg`}
						style="width: 100%"
					/>
				{/each}
			</div>
			<div class="columnc">
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/3.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/7.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/11.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/15.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/18.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/23.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/28.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/29.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/32.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/37.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/41.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/48.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/52.jpg"
					style="width: 100%"
				/>
				<img
					loading="lazy"
					alt="esküvői kreatív fénykép"
					src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/53.jpg"
					style="width: 100%"
				/>
			</div>
		</div>
	</div>
</div>
<Footer />

<style>
	.gallery-title {
		font-size: 24px;
		font-weight: 700;
		margin: 40px 0 24px;
	}

	.gallery {
		padding: 16px;
		background-color: #f5f5f5;
	}

	.gallery {
		text-align: center;
	}

	.rowc {
		display: -ms-flexbox; /* IE10 */
		display: flex;
		-ms-flex-wrap: wrap; /* IE10 */
		flex-wrap: wrap;
		padding: 0 4px;
	}

	/* Create four equal columns that sits next to each other */
	.columnc {
		-ms-flex: 25%; /* IE10 */
		flex: 25%;
		max-width: 25%;
		padding: 0 4px;
	}

	.columnc img {
		margin-top: 8px;
		vertical-align: middle;
		width: 100%;
	}

	/* Responsive layout - makes a two column-layout instead of four columns */
	@media screen and (max-width: 800px) {
		.columnc {
			-ms-flex: 50%;
			flex: 50%;
			max-width: 50%;
		}
	}
</style>

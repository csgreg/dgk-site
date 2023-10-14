<section class="gallery">
	<h3 class="family-gallery-title">Családi képek</h3>
	<div class="rowc">
		<div class="columnc">
			<img
				loading="lazy"
				alt="kisfiú mosolyog"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi6.jpeg"
				style="width: 90%"
			/>
			<img
				loading="lazy"
				alt="kisfiú mosolyog"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi1.jpg"
				style="width: 90%"
			/>
		</div>
		<div class="columnc">
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi2.jpg"
				style="width: 90%"
			/>
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi9.jpg"
				style="width: 90%"
			/>
		</div>
		<div class="columnc">
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi3.jpg"
				style="width: 100%"
			/>
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi4.jpg"
				style="width: 100%"
			/>
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi7.jpeg"
				style="width: 100%"
			/>
		</div>
		<div class="columnc">
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi5.jpg"
				style="width: 90%"
			/>
			<img
				loading="lazy"
				alt="esküvői kép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/gallery/csaladi8.jpeg"
				style="width: 90%"
			/>
		</div>
	</div>
	<div class="contact-section">
		Szeretnél egy családi fotózást?
		<a data-sveltekit-reload class="button is-rounded contact-btn" href="/contact">Írj üzenetet!</a>
	</div>
</section>

<style>
	.gallery {
		padding: 16px;
		background-color: #f5f5f5;
	}

	.contact-section {
		margin-top: 24px;
		margin-bottom: 12px;
		display: flex;
		align-items: center;
		flex-direction: column;
		gap: 8px;
	}

	.contact-btn {
		width: fit-content;
	}

	.family-gallery-title {
		margin-top: 16px;
		font-size: 24px;
		font-weight: 300;
		margin-bottom: 22px;
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

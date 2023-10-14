<section class="gallery">
	<h3 class="family-gallery-title">Termék fotózás</h3>
	<p class="petchy-text">
		Legutóbb volt szerencsénk befotózni a nemrég megalakuló PETCHY családi vállalkozás termékeit.
		Korábban még nem vettünk részt ilyen jellegű fotózáson, de a jövőben szívesen fejlesztenénk
		magunkat ezen a téren is.
	</p>
	<div class="rowc">
		<div class="columnc">
			<img
				loading="lazy"
				alt="kutyaruha reklám termék fénykép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/petchy-photo-01.webp"
				style="width: 90%"
			/>
		</div>
		<div class="columnc">
			<img
				loading="lazy"
				alt="kutyaruha reklám termék fénykép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/petchy-photo-05.webp"
				style="width: 90%"
			/>
		</div>
		<div class="columnc">
			<img
				loading="lazy"
				alt="kutyaruha reklám termék fénykép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/petchy-photo-02.webp"
				style="width: 100%"
			/>
			<img
				loading="lazy"
				alt="kutyaruha reklám termék fénykép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/petchy-photo-03.webp"
				style="width: 100%"
			/>
		</div>
		<div class="columnc">
			<img
				loading="lazy"
				alt="kutyaruha reklám fénykép"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/petchy-photo-04.webp"
				style="width: 90%"
			/>
		</div>
	</div>
	<div class="contact-section">
		Termék fotózás érdekel?
		<a data-sveltekit-reload class="button is-rounded contact-btn" href="/contact">Írj üzenetet!</a>
	</div>
</section>

<style>
	.gallery {
		padding: 16px;
		background-color: #f5f5f5;
	}

	.petchy-text {
		max-width: 700px;
		margin: 0 12px 16px;
		text-align: center;
		margin: auto;
		margin-bottom: 32px;
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
		font-size: 24px;
		font-weight: 300;
		margin-bottom: 22px;
		margin-top: 24px;
		text-align: center;
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

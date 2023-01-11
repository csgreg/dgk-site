<section class="gallery">
	<h1 class="family-gallery-title">Családi képek</h1>
	<div class="rowc">
		<div class="columnc">
			<img alt="esküvői kép" src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/family-photo-01.jpg" style="width: 90%" />
		</div>
		<div class="columnc">
			<img alt="esküvői kép" src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/family-photo-02.jpg" style="width: 90%" />
		</div>
		<div class="columnc">
			<img alt="esküvői kép" src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/family-photo-03-min.jpg" style="width: 100%" />
			<img alt="esküvői kép" src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/family-photo-05.jpg" style="width: 100%" />
		</div>
		<div class="columnc">
			<img alt="esküvői kép" src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/family-photo-04-min.jpg" style="width: 90%" />
		</div>
	</div>
	<div class="contact-section">
		Szeretnél egy családi fotózást?
		<a class="button is-rounded contact-btn" href="/contact">Írj üzenetet!</a>
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
		margin-bottom: 16px;
		font-size: 18px;
		font-weight: 700;
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

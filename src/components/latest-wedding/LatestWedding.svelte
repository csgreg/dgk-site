<script>
	import ImageWCover from '../image-w-cover/ImageWCover.svelte';
</script>

<section>
	<div class="container last-wedding-movie-section">
		<h3 class="last-wedding-movie-title">Előzetesek</h3>
		<div class="columns">
			<div class="column">
				<ImageWCover
					title="Cinti és Sanyi előzetes rövid esküvői videója"
					videoSrc="https://www.youtube.com/embed/Li2zyCljKJo?modestbranding=1"
				/>
			</div>
			<div class="column">
				<div class="video-with-cover">
					<ImageWCover
						title="Eszter és Tibi esküvői előzetes filmje"
						videoSrc="https://www.youtube.com/embed/0D6wnrg_AG0?modestbranding=1"
					/>
				</div>
			</div>
		</div>
	</div>
	<div class="container last-wedding-movie-section">
		<h3 class="last-wedding-movie-title">Esküvői filmek</h3>
		<div class="columns">
			<div class="column">
				<div class="video-with-cover">
					<ImageWCover
						title="Cinti és Sanyi esküvői filmje"
						videoSrc="https://www.youtube.com/embed/vxoW6__K8iQ?modestbranding=1"
					/>
				</div>
			</div>
			<div class="column">
				<div class="video-with-cover">
					<ImageWCover
						title="Eszter és Tibi esküvői filmje"
						videoSrc="https://www.youtube.com/embed/hO8MVtNaIik?modestbranding=1"
					/>
				</div>
			</div>
			<div class="column" />
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

	.video:first-of-type {
		padding-left: 12px;
	}

	.video:last-of-type {
		padding-right: 12px;
	}

	.more-movie-btn {
		margin-bottom: 32px;
	}
</style>

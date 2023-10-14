<script lang="ts">
	export let videoSrc = '';
	export let title = '';
</script>

<div class="video-with-cover">
	<iframe
		{title}
		class="video"
		src={videoSrc}
		allow="accelerometer; autoplay; encrypted-media; gyroscope;"
		allowfullscreen
	/>
</div>

<style>
	.video-with-cover {
		position: relative;
		aspect-ratio: 16 / 9;
		/* width: 500px; */
		max-width: 100%;
	}

	@media screen and (min-width: 800px) {
		.video-with-cover {
			width: 500px;
		}
	}

	.video {
		width: 100%;
		height: 100%;
	}
</style>

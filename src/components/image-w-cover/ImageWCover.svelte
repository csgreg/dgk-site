<script lang="ts">
	export let videoCoverSrc = '';
	export let videoSrc = '';
	export let title = '';
	let videoCoverRef = null;
	let videoRef = null;

	const handleCoverClick = (e) => {
		videoCoverRef.style.display = 'none';
		if (videoRef) {
			// @ts-ignore
			let videoSrc = videoRef.src;
			videoSrc += '&autoplay=1';
			// @ts-ignore
			videoRef.src = videoSrc;
			videoRef.click();
		}
	};
</script>

<div class="video-with-cover">
	<iframe
		{title}
		class="video"
		src={videoSrc}
		allow="accelerometer; autoplay; encrypted-media; gyroscope;"
		allowfullscreen
		bind:this={videoRef}
	/>
	<div
		style={`background-image: url('${videoCoverSrc}');"`}
		class="cover"
		on:click={handleCoverClick}
		bind:this={videoCoverRef}
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

	.cover {
		position: absolute;
		top: 0;
		height: 100%;
		width: 100%;
		cursor: pointer;
		border-radius: 5px;
		box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
		background-repeat: no-repeat, no-repeat;
		background-size: cover;
	}

	.video {
		width: 100%;
		height: 100%;
	}
</style>

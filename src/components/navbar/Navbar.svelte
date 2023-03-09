<script>
	let isActive = false;
	const toggleMenuOpen = () => {
		isActive = !isActive;
	};
</script>

<nav class="navbar" aria-label="main navigation">
	<div class="navbar-brand">
		<a class="navbar-item" href="/">
			<img
				loading="lazy"
				src="https://dgk-site-storage.s3.eu-central-1.amazonaws.com/logo-new.jpeg"
				alt="dgk photography logó"
				class="brand-logo"
			/>
		</a>

		<!-- svelte-ignore a11y-missing-attribute -->
		<a
			role="button"
			class="navbar-burger {isActive && 'is-active'}"
			aria-label="menu"
			aria-expanded="false"
			data-target="navbar"
			on:click={toggleMenuOpen}
			on:keypress={toggleMenuOpen}
		>
			<span aria-hidden="true" />
			<span aria-hidden="true" />
			<span aria-hidden="true" />
		</a>
	</div>

	<div id="navbar" class="navbar-menu {isActive && 'is-active'}">
		<div class="navbar-start">
			<a href="/" class="navbar-item"> Home </a>
			<a href="/gallery" class="navbar-item"> Galéria </a>
			<a href="/movies" class="navbar-item"> Filmek </a>
			<a href="/about" class="navbar-item"> Rólunk </a>
			<a href="/contact" class="navbar-item"> Kapcsolat </a>
		</div>
	</div>
</nav>

<style>
	.navbar {
		box-shadow: rgba(0, 0, 0, 0.15) 0px 5px 15px 0px;
	}

	.brand-logo {
		width: 76px;
		height: 24px;
	}

	.navbar-menu {
		box-shadow: none;
	}

	.navbar-item:hover {
		color: black;
	}
</style>

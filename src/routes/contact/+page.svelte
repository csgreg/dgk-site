<script>
	// @ts-nocheck

	import Copy24 from '../../components/icons/Copy24.svelte';
	import Email24 from '../../components/icons/Email24.svelte';
	import Facebook24 from '../../components/icons/Facebook24.svelte';
	import Phone24 from '../../components/icons/Phone24.svelte';

	const onCopy = (type) => {
		switch (type) {
			case 'phone':
				navigator.clipboard.writeText('+36 30 389 6082');
				break;
			case 'email':
				navigator.clipboard.writeText('photographydgk@gmail.com');
				break;
			case 'facebook':
				navigator.clipboard.writeText('https://www.facebook.com/photographydgk');
				break;
			default:
				break;
		}
	};
</script>

<svelte:head>
	<title>DGK Photography | Kapcsolat</title>
	<meta name="title" content="DGK Photography | Esküvői videó, film és képek készítése" />
	<meta
		name="description"
		content="Csodálatos és egyedi esküvői videót, filmet és képeket készítünk, amik évek múlva is örömöt okoznak. Drónfelvételeket, 4K felbontású videókat készítünk, melyből egy életre szóló filmet vágunk."
	/>
	<meta property="og:title" content="DGK Photography | Esküvői videó, film és képek készítése" />
	<meta
		property="og:description"
		content="Csodálatos és egyedi esküvői videót, filmet és képeket készítünk, amik évek múlva is örömöt okoznak. Drónfelvételeket, 4K felbontású videókat készítünk, melyből egy életre szóló filmet vágunk."
	/>
	<meta property="og:url" content="https://www.photographydgk.hu/contact" />
	<meta name="robots" content="index, follow" />
</svelte:head>

<div class="contact-page">
	<section class="container leave-message-section">
		<form
			method="POST"
			action="https://formsubmit.co/csizmadia99g@gmail.com"
			class="column leave-message-form"
		>
			<h1 class="leave-message-title">Vedd fel velünk a kapcsolatot!</h1>
			<p class="no-info">
				Amennyiben nem rendelkezel még információval a pontos helyszínről, időpontról azt hagyd
				üresen!
			</p>
			<input name="name" class="input is-normal inp" type="text" placeholder="Név" />
			<input type="hidden" name="_captcha" value="false" />
			<input type="hidden" name="_subject" value="New email from website!" />
			<input type="hidden" name="_next" value="https://photographydgk.com/contact.html" />
			<input name="phone" class="input is-normal inp" type="text" placeholder="Telefonszám" />
			<input name="email" class="input is-normal inp" type="text" placeholder="Email" />
			<input name="date" class="input is-normal inp" type="text" placeholder="Dátum és helyszín" />
			<textarea name="expandables" class="textarea" placeholder="Részletek" />
			<button type="submit" class="button is-dark message-form-submit">Küldés</button>
		</form>
		<div class="contact-infos">
			<div class="contect-line">
				<Phone24 /> <span class="contact-line-info">+36 30 389 6082</span>
				<span on:keydown={() => onCopy('phone')} on:click={() => onCopy('phone')} class="copy-info"
					><Copy24 /></span
				>
			</div>
			<div class="contect-line">
				<Email24 /> <span class="contact-line-info">photographydgk@gmail.com</span>
				<span on:keydown={() => onCopy('email')} on:click={() => onCopy('email')} class="copy-info"
					><Copy24 /></span
				>
			</div>
			<div class="contect-line">
				<Facebook24 />
				<a href="https://www.facebook.com/photographydgk" class="contact-line-info"
					>@photographydgk</a
				>
				<span
					on:keydown={() => onCopy('facebook')}
					on:click={() => onCopy('facebook')}
					class="copy-info"><Copy24 /></span
				>
			</div>
		</div>
	</section>
</div>

<style>
	.contact-page {
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.leave-message-section {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.leave-message-title {
		font-size: 24px;
		font-weight: 600;
		margin: 40px 0 12px;
		width: 100%;
	}

	.no-info {
		margin: 0 12px 24px;
		text-align: left;
	}

	.leave-message-form {
		max-width: 600px;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.inp {
		margin-bottom: 12px;
	}

	.message-form-submit {
		margin-top: 24px;
		max-width: 100px;
	}

	.contact-infos {
		margin-top: 24px;
		display: flex;
		flex-direction: column;
		gap: 12px;
		margin-bottom: 40px;
	}

	.contect-line {
		display: flex;
		gap: 8px;
		justify-content: center;
	}

	.copy-info {
		color: rgb(174, 174, 174);
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 2px;
	}

	.copy-info:hover {
		cursor: pointer;
		border-radius: 4px;
		color: rgb(137, 137, 137);
		background-color: rgb(234, 234, 234);
	}

	.copy-info:active {
		cursor: pointer;
		border-radius: 4px;
		color: rgb(87, 87, 87);
		background-color: rgb(220, 220, 220);
	}
</style>

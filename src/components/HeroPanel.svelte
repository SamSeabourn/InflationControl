<script lang="ts">
	import { base } from '$app/paths';
</script>

<section id="hero">
	<slot />
</section>
<div class="hero-image" style="background-image: url({base + '/rescue-banner.webp'})" />
<div class="gradient-overlay" />

<style>
	section {
		width: 100%;
		height: 74vh;
		padding-top: 5rem;
		background-color: #f2f3f6;
	}

	.hero-image {
		position: absolute;
		top: 0rem;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		height: 75rem;
		width: 100%;
	}

	.gradient-overlay {
		position: absolute;
		width: 80%;
		height: 150%;
		top: 0;
		background: linear-gradient(90deg, rgba(0, 0, 0, 1) 0%, rgba(0, 0, 0, 0) 100%);
	}

	@media (max-width: 500px) {
		.gradient-overlay {
			position: absolute;
			width: 75%;
			height: 150%;
			top: 0;
			background: linear-gradient(90deg, rgba(0, 0, 0, 1) 0%, rgba(0, 0, 0, 0) 100%);
		}
	}
</style>

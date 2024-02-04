<script lang="ts">
	import { base } from '$app/paths';
	export let title: string;
</script>

<nav>
	<a href="{base}/">
		<img src="{base}/logo.png" alt="Inflation Control Logo"  />
		<h1 aria-label={title}>{title}</h1>
	</a>
</nav>

<style>
	@font-face {
		font-family: 'Inter-SemiBold';
		src: url('$lib/assets/fonts/Inter-SemiBold.ttf');
		font-display: swap;
	}
	nav {
		height: 6rem;
		width: 100%;
		box-shadow: 0px 4px 24px 0px rgba(0, 0, 0, 0.15);
		display: flex;
		align-items: center;
		position: fixed;
		background-color: #f4d933;
		z-index: 30;
	}
	h1 {
		margin-left: 2.5rem;
		font-family: 'Inter-SemiBold', sans-serif;
		font-size: 2.7rem;
		font-weight: 900;
		letter-spacing: -0.15rem;
	}

	img {
		margin-left: 2rem;
		height: 4.5rem;
		margin-left: 3rem;
	}

	a {
		font-family: 'Inter-SemiBold', sans-serif;
		display: flex;
		color: #170d1e;
		text-decoration: none;
		display: flex;
		align-items: center;
	}

	@media (max-width: 500px) {
		h1 {
			font-size: 2rem;
		}
	}

	a:hover,
	a:visited {
		color: #170d1e;
		text-decoration: none;
	}
</style>

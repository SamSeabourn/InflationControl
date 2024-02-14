<script lang="ts">
	export let href: string;
	export let aTagText: string;
</script>

<p>
	<a {href}>{aTagText}</a>
</p>

<style>
	@font-face {
		font-family: 'GeneralSans-Variable';
		src: url('$lib/assets/fonts/GeneralSans-Variable.woff2');
		font-display: swap;
	}

	p {
		color: #170d1e;
		font-family: 'GeneralSans-Variable', sans-serif;
		font-size: 3rem;
		font-style: normal;
		font-weight: 600;
		line-height: 2.85rem;
	}

	@media (max-width: 1640px) {
		p {
			max-width: 49rem;
			font-size: 2.5rem;
			line-height: 2.2rem;
		}
	}
	a {
		color: #170d1e;
		cursor: pointer;
		font-family: 'GeneralSans-Variable', sans-serif;
		text-decoration: underline .25rem #f4d933;
	}

	a:hover {
		color: #170d1e;
		opacity: 0.8;
		cursor: pointer;
		font-weight: 600;
		text-decoration: none;
	}
</style>

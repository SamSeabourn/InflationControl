<script lang="ts">
	export let label: string;
</script>

<h1 aria-label={label}><slot /><span>.</span></h1>

<style>
	@font-face {
		font-family: 'GeneralSans-Variable';
		src: url('$lib/assets/fonts/GeneralSans-Variable.woff2');
		font-display: swap;
	}

	h1,
	span {
		margin: 2.5rem 0;
		font-weight: 600;
		font-family: 'GeneralSans-Variable';
		font-size: 3rem;
	}

	h1 {
		color: #170d1e;
	}

	span {
		color: #f4d933;
	}
</style>

<script lang="ts">
	export let iconURL: string;
	export let iconAlt: string;
</script>

<div>
	<img src={iconURL} alt={iconAlt} />
	<span class="wrapper">
		<slot />
	</span>
</div>

<style>
	@font-face {
		font-family: 'Inter';
		src: url('$lib/assets/fonts/Inter-Regular.ttf');
		font-display: swap;
	}
	div {
		display: flex;
		align-items: center;
		margin-top: 1.25rem;
	}
	.wrapper {
		font-family: 'Inter', sans-serif;
		color: #170d1e;
		margin-left: 0.5rem;
		font-size: 1.5rem;
		font-weight: 600;
	}
</style>

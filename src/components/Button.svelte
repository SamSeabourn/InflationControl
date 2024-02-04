<script lang="ts">
	export let btnFunc: () => object;
</script>

<button on:click={() => btnFunc()}>
	<slot />
</button>

<style>
	button {
		width: 13rem;
		height: 3.5rem;
		background-color: #f4d933;
		border: none;
		font-size: 1rem;
		font-weight: 700;
		border-radius: 2rem;
	}

	button:hover {
		background-color: transparent;
		border: 3px solid #f4d933;
		color: black;
		font-size: 1rem;
		border-radius: 2rem;
		cursor: pointer;
	}
</style>

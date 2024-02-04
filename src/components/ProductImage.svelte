<script lang="ts">
	export let imageSource: string;
	export let desc: string
</script>

<div role="img" aria-label={desc} style="background-image: url({imageSource});"></div>

<style>
	div {
		height: 9.5rem;
		display: flex;
		width: 13.5rem;
		border-radius: 0.5rem; 
		background-color: #fff;
		filter: drop-shadow(0px 0px 6px rgba(0, 0, 0, 0.2));
		justify-content: center;
		align-items: center;
		margin-right: 1rem;
		margin-top: 1rem;
		background-size: cover;
		background-position: center;
	}
</style>

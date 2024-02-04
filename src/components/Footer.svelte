<footer>
	<div class="wrapper">
		<a href="https://www.samseabourn.com" target="_blank"
			><span class="mailbox"></span> Site by Sam Seabourn</a
		>
	</div>
</footer>

<style>
	@font-face {
		font-family: 'GeneralSans-Variable';
		src: url('$lib/assets/fonts/GeneralSans-Variable.woff2');
		font-display: swap;
	}

	footer {
		width: 100%;
		height: 3.25rem;
		background-color: #f4d933;
		display: flex;
	}

	.mailbox {
		font-size: 1.5rem;
	}

	.wrapper {
		align-items: center;
		display: flex;
		width: 100%;
		padding: 0 2rem;
		justify-content: space-between;
	}

	a {
		color: #170d1e;
		font-family: 'GeneralSans-Variable', sans-serif;
		font-size: 1rem;
		font-style: normal;
		font-weight: 500;
		line-height: 1rem;
		letter-spacing: 0.02rem;
		text-decoration: none;
		transition: opacity 200ms ease-in-out;
	}

	span {
		color: #170d1e;
		opacity: 0.7;
		font-family: 'GeneralSans-Variable', sans-serif;
		font-size: 1rem;
		font-style: normal;
		font-weight: 500;
		line-height: 1rem;
		letter-spacing: 0.02rem;
	}

	a:hover {
		opacity: 0.5;
	}
</style>

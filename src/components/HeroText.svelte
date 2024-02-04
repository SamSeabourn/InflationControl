<div class="container">
	<p>
		SEALING, LIFTING AND <br />
		EMERGENCY AIR BAGS
	</p>
</div>

<style>
	@font-face {
		font-family: 'GeneralSans-Variable';
		src: url('$lib/assets/fonts/GeneralSans-Variable.woff2');
		font-display: swap;
	}

	p {
		font-family: 'GeneralSans-Variable';
		font-size: 4.75rem;
		font-weight: 500;
		color: #fdfdfd;
		z-index: 10;
		text-rendering: optimizelegibility;
		filter: drop-shadow(0px 0px 1.3rem rgba(0, 0, 0, 0.5));
	}

	@media (max-width: 1280px) {
		p {
			z-index: 10;
		}

		div {
			max-width: 59vw;
		}
	}

	span {
		transition: opacity 450ms ease-in;
	}

	.container {
		height: 100%;
		margin-left: 9.5rem;
		display: flex;
		align-items: center;
	}

	.typed-text {
		font-weight: 600;
		filter: drop-shadow(0px 3px 9px rgba(0, 0, 0, 0.1));
		transition: color 500ms ease-in-out;
	}

	.cursor {
		display: inline-block;
		height: 4.25rem;
		width: 0.625rem;
		margin-left: 0.5rem;
		transform: translate(-0.3125rem, 0.45rem);
		background-color: #05d2d9;
		animation: flash 800ms linear infinite;
	}

	@keyframes flash {
		50% {
			opacity: 0;
		}
	}

	@media (max-width: 500px) {
		.container {
			margin-left: 4.25rem;
		}
		p {
			font-size: 4rem;
		}
	}
</style>

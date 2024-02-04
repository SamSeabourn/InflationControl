<script>
	import { base } from '$app/paths';
	import AirGap from '../components/AirGap.svelte';
	import Button from '../components/Button.svelte';
	import CTA from '../components/CTA.svelte';
	import CTA2 from '../components/CTA2.svelte';
	import ContentPadding from '../components/ContentPadding.svelte';
	import ContentPanel from '../components/ContentPanel.svelte';
	import FadeInOnScroll from '../components/FadeInOnScroll.svelte';
	import Footer from '../components/Footer.svelte';
	import HeroPanel from '../components/HeroPanel.svelte';
	import HeroText from '../components/HeroText.svelte';
	import LogoPuck from '../components/LogoPuck.svelte';
	import NavBar from '../components/NavBar.svelte';
	import Paragraph from '../components/Paragraph.svelte';
	import ProductImage from '../components/ProductImage.svelte';
	import Title from '../components/Title.svelte';
</script>

<NavBar title={'INFLATION CONTROL'} />
<HeroPanel>
	<HeroText />
</HeroPanel>
<ContentPanel>
	<ContentPadding>
		<Title label="About Us">About Us</Title>
		<Paragraph>
			As the exclusive New Zealand agent for Vetter lifting and pipe sealing bags, we
			specialise in high-quality pipe sealing, bypass, and testing plugs, vital for
			professionals in wastewater, mains, and domestic drainage sectors. We also cater to your
			lifting needs with our range of innovative lifting bags for rescue teams.
		</Paragraph>
		<AirGap />
		<FadeInOnScroll id="vetter">
			<Title label="Vetter">Vetter</Title>
			<Paragraph>
				Vetter specializes in high-pressure inflatable tools for emergency teams. Known for
				their robust air bags, ideal for lifting vehicles and debris, and pipe sealing bags,
				crucial for sealing and redirecting fluid leaks, Vetter products are essential in
				managing rescue operations and emergency scenarios efficiently and safely
			</Paragraph>
		</FadeInOnScroll>
		<FadeInOnScroll id="vetterLinks">
			<img src="{base}/vetter-logo.svg" alt="Vetter Logo" style="height: 13rem" />
			<br />
			<Button btnFunc={async () => window.open('https://vetter.de/en/', '_blank')}>
				Vetter's Website
			</Button>
		</FadeInOnScroll>
		<AirGap />
		<FadeInOnScroll id="pipeSealing">
			<Title label="Pipe Sealing">Pipe Sealing</Title>
			<Paragraph>
				Vetter Pipe Sealing bags are an ideal choice for fast and dependable drainage
				sealing, offering the flexibility of adjustable contact pressure to suit various
				requirements
			</Paragraph>
			<div style="display:flex">
				<ProductImage desc="Pipe sealing bag diagram" imageSource="{base}/pipe01.png" />
				<ProductImage desc="Large emergency bag getting inserted into a pipe" imageSource="{base}/pipe02.png" />
				<ProductImage desc="Range of pipe sealing bags" imageSource="{base}/pipe03.png" />
				<ProductImage desc="Range of large pipe sealing bags" imageSource="{base}/pipe04.png" />
			</div>
			<br />
			<Button btnFunc={async () => window.open('https://vetter.de/en/market-specific-solutions/hazmat-program/sealing-pipelines-and-gullies/', '_blank')}>
				View Products
			</Button>
		</FadeInOnScroll>
		<AirGap/>
		<FadeInOnScroll id="liftingBag">
			<Title label="Emergency Lifting Bags">Lifting Bags</Title>
			<Paragraph>
				Vetter's Pneumatic Lifting Bags are an essential tool for rescue operations, ideal
				for lifting vehicles or any large debris. Engineered in Germany, Vetter lifting bag
				ensure precision and safety with even pressure distribution and a stable, anti-slip
				surface for challenging environments.
			</Paragraph>
			<div style="display:flex">
				<ProductImage desc="Pneumatic lifting bag lifting rubble" imageSource="{base}/lift01.png" />
				<ProductImage desc="Lifting bag example" imageSource="{base}/lift02.png" />
				<ProductImage desc="Thin lifting bag between slabs" imageSource="{base}/lift03.png" />
				<ProductImage desc="Lifting 112 tons with a lifting bag" imageSource="{base}/lift04.png" />
			</div>
			<br />
			<Button btnFunc={async () => window.open('https://vetter.de/en/market-specific-solutions/emergency-pneumatics/lifting-bags/', '_blank')}>
				View Products
			</Button>
		</FadeInOnScroll>
		<AirGap/>
		<FadeInOnScroll id="cta">
			<CTA2 href={'https://vetter.de/media/pdf/ba/78/00/2206_VET_Katalog_1_Rettung_Gefahrgut_EN_Web.pdf'} aTagText={"here"}>
				View the full Vetter product range
			</CTA2>
		</FadeInOnScroll>
		<AirGap />
	</ContentPadding> 
	<Footer />
</ContentPanel>

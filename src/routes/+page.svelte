<script lang="ts">
	import About from '../components/About.svelte';
	import Contact from '../components/Contact.svelte';
	import EmailList from '../components/EmailList.svelte';
	import Experience from '../components/Experience.svelte';
	import Footer from '../components/Footer.svelte';
	import PortfolioHeader from '../components/PortfolioHeader.svelte';
	import Skills from '../components/Skills.svelte';
	import Work from '../components/Work.svelte';
	import Writings from '../components/Writings.svelte';
</script>

<svelte:head>
	<title>Portfolio | Maruf Shafique</title>
	<meta
		name="Maruf Shafique"
		content="Portfolio of Maruf Shafique. A freelance software engineer."
	/>
</svelte:head>

<section>
	<PortfolioHeader />

	<Work />

	<Writings />

	<About />

	<Experience />

	<Skills />

	<Contact />

	<EmailList />

	<Footer />
</section>

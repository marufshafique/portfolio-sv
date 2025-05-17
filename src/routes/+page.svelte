<script lang="ts">
	import PortfolioHeader from '../components/PortfolioHeader.svelte';
	import Work from '../components/Work.svelte';
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
</section>

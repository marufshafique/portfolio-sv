<script>
	import Button from './Button.svelte';
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';
</script>

<section class="md:sm-32 mt-10 sm:mt-16">
	<Container>
		<SectionHeader title="Email lists" />
		<h1 class="text-7xl font-medium">Get design insights and articles straight to your inbox</h1>

		<div class="mt-16">
			<div class="flex gap-8">
				<input class="w-1/3 rounded p-3" type="text" />
				<Button>Subscribe</Button>
			</div>
			<p class="mt-2 text-gray-500">No spam, unsubscribe at any time.</p>
		</div>
	</Container>
</section>

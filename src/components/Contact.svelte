<script>
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';
</script>

<section class="md:sm-32 mt-10 sm:mt-16">
	<Container>
		<SectionHeader title="Get in touch" />

		<h1 class="my-16 text-7xl">Have a project in mind?</h1>

		<div class="grid grid-cols-3 gap-16">
			<div class="col-span-2 space-y-8">
				<p class="text-2xl">If you want to chat about a project — email me on hi@email.com.</p>
				<p class="text-2xl">
					I can help designing a new website, designing a new digital product, building a strong
					design system, and building websites in Framer.
				</p>
				<p class="text-2xl">Currently based in Lisbon — available for remote-friendly work.</p>
			</div>
			<div class="flex flex-col">
				<a class="mb-4 w-fit border-b-2 border-gray-300 text-xl" href="#">Github</a>
				<a class="mb-4 w-fit border-b-2 border-gray-300 text-xl" href="#">LinkedIn</a>
				<a class="mb-4 w-fit border-b-2 border-gray-300 text-xl" href="#">Twitter</a>
			</div>
		</div>
	</Container>
</section>

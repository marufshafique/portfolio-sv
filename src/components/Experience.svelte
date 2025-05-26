<script>
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';

	const experiences = [
		{
			position: 'Freelance 1',
			title: 'Freelans Web developer',
			date: 'Jun 2022 - Present'
		},
		{
			position: 'Freelance 2',
			title: 'Freelans Web developer',
			date: 'Jun 2022 - Present'
		},
		{
			position: 'Freelance 3',
			title: 'Freelans Web developer',
			date: 'Jun 2022 - Present'
		},
		{
			position: 'Freelance 4',
			title: 'Freelans Web developer',
			date: 'Jun 2022 - Present'
		}
	];
</script>

<section class="mt-10 sm:mt-16 md:mt-32">
	<Container>
		<div class="grid gap-16 lg:grid-cols-2">
			<div>
				<SectionHeader title="Experience" />
			</div>

			<div class="space-y-16 mt-4">
				{#each experiences as experience}
					<div>
						<h3 class="text-3xl font-medium mb-2">{experience.position}</h3>
						<p class="text-3xl text-gray-500 mb-2">{experience.title}</p>
						<p class="text-2xl text-gray-500">{experience.date}</p>
					</div>
				{/each}
			</div>
		</div></Container
	>
</section>

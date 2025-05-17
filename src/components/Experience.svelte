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
		<SectionHeader title="Experience" />

		<div>
			{#each experiences as experience}
				<div class="mt-8">
					<h3 class="text-2xl font-medium">{experience.position}</h3>
					<p class="text-lg text-gray-500">{experience.title}</p>
					<p class="text-lg text-gray-500">{experience.date}</p>
				</div>
			{/each}
		</div>
	</Container>
</section>

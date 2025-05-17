<script>
	import Container from './Container.svelte';
	import HorizontalLine from './HorizontalLine.svelte';
	import Project from './Project.svelte';
	import SectionHeader from './SectionHeader.svelte';

	const works = [
		{
			title: 'Project 1',
			url: 'https://placehold.co/600x400',
			desc: 'Lorem ipsum dolor sit amet.'
		},
		{
			title: 'Project 2',
			url: 'https://placehold.co/600x400',
			desc: 'Lorem ipsum dolor sit amet.'
		},
		{
			title: 'Project 3',
			url: 'https://placehold.co/600x400',
			desc: 'Lorem ipsum dolor sit amet.'
		},
		{
			title: 'Project 4',
			url: 'https://placehold.co/600x400',
			desc: 'Lorem ipsum dolor sit amet.'
		},
		{
			title: 'Project 5',
			url: 'https://placehold.co/600x400',
			desc: 'Lorem ipsum dolor sit amet.'
		}
	];
</script>

<Container>
	<section class="mt-10 sm:mt-16 md:mt-32">
		<SectionHeader title="Work" />

		<div class="gap-8 pt-16 md:grid md:grid-cols-2">
			{#each works as work, i}
				<a href="" class={`${i === 0 ? 'col-span-2' : ''}`}>
					<Project title={work.title} url={work.url} desc={work.desc} />
				</a>
			{/each}
		</div>
	</section>
</Container>

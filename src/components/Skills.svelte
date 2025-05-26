<script lang="ts">
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';

	const skills = ['Frontend Development', 'Backend Development', 'UX Design', 'Product Strategy'];
</script>

<section class="md:sm-32 mt-10 sm:mt-16">
	<Container>
		<SectionHeader title="Skills" />

		<div class="mt-8">
			{#each skills as skill}
				<h1 class="text-6xl font-medium border-b border-gray-200 py-10">{skill}</h1>
			{/each}
		</div>
	</Container>
</section>

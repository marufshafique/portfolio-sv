<script lang="ts">
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';

	const skills = ['Frontend Development', 'Backend Development', 'UX Design', 'Product Strategy'];
</script>

<section class="md:sm-32 mt-10 sm:mt-16">
	<Container>
		<SectionHeader title="Skills" />

		<div class="space-y-10">
			{#each skills as skill}
				<h1 class="border-b border-gray-200 pb-10 text-6xl font-medium">{skill}</h1>
			{/each}
		</div>
	</Container>
</section>

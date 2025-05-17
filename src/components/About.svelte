<script>
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';
</script>

<Container>
	<SectionHeader title="About" />

	<div class="grid grid-cols-2 gap-32 mt-16">
		<div>
			<p class="text-3xl font-medium">
				I’m Ben — a freelance digital product designer with 10 years of experience. I care a lot
				about using design for positive impact. Currently based in Lisbon, Portugal.
			</p>
		</div>
		<div class="space-y-8">
			<p class="text-2xl">
				I was most recently working at Portugal’s newest unicorn, Cucumber. They raised the biggest
				Series D Portugal has seen. Before that I worked for Cool Cool — the fastest growing bank in
				Portugal. I led product design for over 8 million customers. I worked across multiple
				product squads solving complex money problems.
			</p>
			<p class="text-2xl">
				Before Cool Cool — I was the first design-hire at tech startup, Red Box. I led all of Red
				Box’s design output. From advertising, to the website, to the digital dashboard product. I
				was the 2nd hire and the company grew to 200 whilst there.
			</p>
			<p class="text-2xl">
				Over the years I’ve worked in automotive, health-tech, banking, SaaS and telecoms. From
				early-stage startups, to FTSE 100 companies.
			</p>
		</div>
	</div>
</Container>

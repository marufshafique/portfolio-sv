<script lang="ts">
	import BlogPost from './BlogPost.svelte';
	import Container from './Container.svelte';
	import SectionHeader from './SectionHeader.svelte';

	const blog_posts = [
		{
			title: 'The making of your favorite products 1',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'The making of your favorite products',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'The making of your favorite products 3',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'The making of your favorite products 4',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'The making of your favorite products 5',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		}
	];
</script>

<section class="mt-10 sm:mt-16 md:mt-32">
	<Container>
		<div class="grid gap-16 lg:grid-cols-2">
			<div>
				<SectionHeader title="Writings" />
			</div>

			<div class="mt-8 space-y-8 md:mt-0">
				<h3 class="text-2xl">Blog posts</h3>

				{#each blog_posts as post}
					<BlogPost title={post.title} date={post.date} />
				{/each}

				<div class="my-8">
					<a class="text-xl font-medium text-gray-700 underline" href="">View All Writings</a>
				</div>
			</div>
		</div>
	</Container>
</section>

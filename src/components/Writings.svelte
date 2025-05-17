<script lang="ts">
	import BlogPost from './BlogPost.svelte';
	import Container from './Container.svelte';
	import HorizontalLine from './HorizontalLine.svelte';

	const blog_posts = [
		{
			title: 'Blog Post 1',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'Blog Post 2',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'Blog Post 3',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'Blog Post 4',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		},
		{
			title: 'Blog Post 5',
			date: 'Jan 23, 2023',
			url: 'https://placehold.co/600x400'
		}
	];
</script>

<section>
	<Container>
		<HorizontalLine />
		<h1 class="text-5xl font-medium">Writings</h1>
		<h3 class="mt-8 text-2xl">Blog posts</h3>

		<div class="mt-8 space-y-8">
			{#each blog_posts as post}
				<BlogPost title={post.title} date={post.date} />
			{/each}
			<div class="my-8">
				<a class="text-xl font-medium text-gray-700 underline" href="">View All Writings</a>
			</div>
		</div>
	</Container>
</section>

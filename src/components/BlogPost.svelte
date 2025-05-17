<script lang="ts">
	interface Props {
		title: string;
		date: string;
	}

	const props: Props = $props();
</script>

<div class="border-b border-b-gray-200 pb-12">
	<h1 class="mb-3 text-2xl font-medium md:text-3xl">{props.title}</h1>
	<p class="flex text-lg">
		{props.date} <span class="mx-4">·</span> <span> 0 min read.</span>
	</p>
</div>

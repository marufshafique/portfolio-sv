<script lang="ts">
	interface Props {
		title: string;
		date: string;
	}

	const props: Props = $props();
</script>

<div>
	<h1 class="text-2xl font-medium md:font-3xl">{props.title}</h1>
	<p class="flex text-lg">{props.date} <span class="ml-4">·  0 min read.</span></p>
</div>

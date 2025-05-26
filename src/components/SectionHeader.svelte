<script lang="ts">
	import HorizontalLine from './HorizontalLine.svelte';

	interface Props {
		title: string;
	}

	const props: Props = $props();
</script>

<div class="mb-20">
	<HorizontalLine />
	<h1 class="text-5xl font-medium">{props.title}</h1>
</div>

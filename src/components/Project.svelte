<script lang="ts">
	import { ArrowRight } from '@lucide/svelte';

	interface Props {
		title: string;
		url: string;
		desc: string;
	}
	const props: Props = $props();
</script>

<div>
	<img class="w-full" src={props.url} alt="Screenshot of project landing page" />
	<h3 class="flex items-center pt-6 text-xl font-medium md:text-2xl">
		{props.title}
		<ArrowRight class="ml-2" />
	</h3>

	<p class="text-lg sm:text-xl">{props.desc}</p>
</div>

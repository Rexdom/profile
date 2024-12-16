<script lang="ts">
	interface Props {
		className: string;
		title: string;
	}

	let { className, title }: Props = $props();
</script>

<div class={`${className} bg-yellow-300 text-lg`}>{title}</div>

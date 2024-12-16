<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import '../app.css';
	let { children } = $props();
</script>

<div class="min-h-screen bg-gradient-to-r from-[#a8edea] to-[#fed6e3] px-[5%] py-6 md:px-[10%]">
	<Header />
	{@render children()}
</div>

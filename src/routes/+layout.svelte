<script>
	import favicon from '/favicon2.png';
	import '../app.css';

	let { children } = $props();
</script>


<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<main>
	{@render children()}
</main>

<script>
	import 'uno.css';
	import '../app.css';
	import '$asset/stylesheet/global.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
	<link
		href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300..700;1,9..144,300..500&family=Public+Sans:ital,wght@0,300..800;1,300..800&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

{@render children()}

<script>
	import Footer from '$lib/components/Footer.svelte';
	import Header from '$lib/components/Header.svelte';
	import '../global.css';
</script>

<svelte:head>
	<meta name="description" content="Ритуальный дом 62 | г. Рязань" />
	<title>Ритуальный дом 62</title>
</svelte:head>
<div id="container">
	<Header />
	<main>
		<slot />
	</main>
	<Footer />
</div>

<style>
	#container {
		display: flex;
		flex-direction: column;
		align-items: stretch;
		background-color: #101820;
		color: white;
	}
</style>

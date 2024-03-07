<script>
	import '../app.css';
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<main class="bg-[#171717] min-h-screen flex flex-col justify-between px-5 md:px-50">
	<Header />
		<div class="flex-1">
			<slot />
		</div>
	<Footer />
</main>
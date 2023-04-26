<script>
	import Navbar from '../components/navbar.svelte';
	let styles = {
		gradient: 'bg-gradient-to-r from-green-200 via-green-400 to-green-500',
		glassmorphism:
			'bg-gray-400 bg-clip-padding backdrop-filter backdrop-blur-lg bg-opacity-10 border border-gray-100'
	};
</script>

<div id="appContainer" class={`h-screen px-5`}>
	<Navbar />
	<div
		class="flex justify-center items-center rounded-2xl h-1/2 bg-gradient-to-r from-yellow-400 to-amber-200"
	>
		<div class=" text-white font-bold text-4xl">shreyas-shriyan.github.io</div>
	</div>
</div>

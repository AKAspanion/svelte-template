<script>
	import Header from './Header.svelte';
	import '../app.postcss';
	import './styles.css';
</script>

<div class="flex flex-col min-h-screen">
	<Header />

	<main class="flex flex-1 flex-col p-4 w-full max-w-5xl mx-auto mt-0">
		<slot />
	</main>

	<footer class="flex flex-col justify-center items-center p-3">
		<p>
			visit <a class="font-bold" href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit
		</p>
	</footer>
</div>

<style>
	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>

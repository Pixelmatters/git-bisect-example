<script>
	import Animation from "./Animation.svelte";
</script>

<main>
	<h1>Git Bisect Example</h1>

	<div class="animationWrapper">

		<Animation />
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	.animationWrapper {
		margin: 0 auto;
		padding: 16px 0;
		max-width: 400px;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>

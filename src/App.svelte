<script>
	export let name;
</script>

<main>
	<h1>Welcome to {name}!</h1>
	<p>Visit this <a href="https://7streams.vercel.app/view1">website</a> to learn more about this app.</p>
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

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>

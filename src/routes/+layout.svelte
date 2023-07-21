<script>
	import '../app.scss';
</script>

<header />

<main>
	<slot />
</main>

<style lang="scss">
	main {
		min-height: 100dvh;
		width: 100%;
		background-color: red;
	}
</style>

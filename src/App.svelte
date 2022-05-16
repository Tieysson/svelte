<script>
	import Router from "svelte-spa-router";
	import Home from "./routes/Home.svelte";
	import NotFound from "./routes/NotFound.svelte";

	let routes = {
		"/": Home,

		"*": NotFound,
	};
</script>

<main>
	<Router {routes} />
</main>

<style>
</style>

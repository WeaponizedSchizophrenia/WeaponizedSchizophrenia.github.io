<script>
	import { base } from '$app/paths';
</script>

<nav>
	<a href="{base}/">Pagrindinis</a>
	<a href="{base}/di">Dirbtinis intelektas</a>
	<a href="{base}/apie">Apie</a>
</nav>

<slot />

<style>
	:global(*) {
		margin: 0;
		padding: 0;
	}
	:global(a) {
		color: white;
	}
	:global(a:hover) {
		color: lightskyblue;
	}
	nav {
		position: sticky;
		top: 0;
		display: flex;
		background: black;
		padding: 1.25rem 1rem;
		user-select: none;
	}
	a {
		color: #ababab;
		margin: 0.25rem 0.5rem;
		text-decoration: none;
		transition: transform 0.1s ease-in-out;
		font-size: 1.2rem;
	}
	a:hover {
		color: #cccccc;
		text-decoration: underline;
		transform: translateY(-0.1rem);
		transition: transform 0.1s ease-in-out;
	}
</style>

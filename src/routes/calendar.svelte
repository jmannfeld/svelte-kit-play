<script context="module">
	export const prerender = true;
</script>

<svelte:head>
	<title>Calendar</title>
	<meta name="description" content="Svelte calendar" />
</svelte:head>

<div class="content">
	<h1>Svelte Calendar</h1>
	<p>Things to do will go here.</p>
</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}
</style>

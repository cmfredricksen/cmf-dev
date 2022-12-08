<script lang="ts">
	const links = [
		{
			title: 'Home',
			path: '/'
		},
		{
			title: 'About',
			path: '/about'
		},
		{
			title: 'Contact',
			path: '/contact'
		}
	];
</script>

<nav>
	{#each links as { title, path }}
		<a href={path}>{title}</a>
	{/each}
</nav>

<style>
	a {
		margin: 0 1rem;
	}
</style>

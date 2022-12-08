<script lang="ts">
	import '../global.css';
	import Header from '$lib/header.svelte';
</script>

<Header />
<div class="wrapper">
	<slot />
</div>

<style>
	.wrapper {
		width: 70%;
		margin: 4rem auto;
	}
</style>

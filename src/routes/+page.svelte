<script>
	import { browser } from '$app/environment';
	import Test from '../components/test.svelte';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<br />
{#if browser}
	<Test />
{/if}
<Test />

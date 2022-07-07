<script lang="ts">
	import "../app.css";
	import "@fontsource/plus-jakarta-sans/variable.css";
	import { _api } from '@iconify/react';
	import fetch from 'cross-fetch';

	_api.setFetch(fetch); // for iconify SSR support
</script>

<main>
	<slot />
</main>

<footer>
</footer>

<style>
</style>

<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Icon from '@iconify/svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>
<section class="h-screen flex justify-center items-center">
	<div class="flex flex-col w-screen items-center space-y-8 max-w-md md:max-w-none">
		<h1 class="text-center">Quack! RoastedDuck here.</h1>
		<div class="flex space-x-4">
			<a href="https://github.com/roastedduk" class="icon"><Icon icon="tabler:brand-github" width="32"/></a>
			<a href="https://twitter.com/roastedduk" class="icon"><Icon icon="tabler:brand-twitter" width="32"/></a>
			<a href="https://discordapp.com/users/297958693293654016" class="icon"><Icon icon="tabler:brand-discord" width="32"/></a>
			<a href="https://t.me/roasted_duck" class="icon"><Icon icon="tabler:brand-telegram" width="32"/></a>
		</div>
		<div>
			There's more to come!
		</div>
	</div>
</section>

<style>
	.icon {
		@apply hover:scale-110 transition-all hover:bg-black dark:hover:bg-white hover:bg-opacity-10 dark:hover:bg-opacity-10 rounded-full p-3;
	}
</style>

<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Icon, { addIcon } from '@iconify/svelte/dist/OfflineIcon.svelte';
	
	import github from '@iconify-icons/tabler/brand-github.js';
	import twitter from '@iconify-icons/tabler/brand-twitter.js';
	import discord from '@iconify-icons/tabler/brand-discord.js';
	import telegram from '@iconify-icons/tabler/brand-telegram.js';
	addIcon('github', github);
	addIcon('twitter', twitter);
	addIcon('discord', discord);
	addIcon('telegram', telegram);
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>
<section class="h-screen flex justify-center items-center mx-6">
	<div class="flex flex-col w-screen items-center space-y-8 max-w-md md:max-w-none">
		<h1 class="text-center">Quack! RoastedDuck here.</h1>
		<div class="flex space-x-4">
			<a href="https://github.com/roastedduk" class="icon"><Icon icon="github" width="32"/></a>
			<a href="https://twitter.com/roastedduk" class="icon"><Icon icon="twitter" width="32"/></a>
			<a href="https://discordapp.com/users/297958693293654016" class="icon"><Icon icon="discord" width="32"/></a>
			<a href="https://t.me/roasted_duck" class="icon"><Icon icon="telegram" width="32"/></a>
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

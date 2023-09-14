<script>
	import { Search, Button } from 'flowbite-svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="h-screen w-screen">
	<div
		class="h-full w-full bg-cover bg-no-repeat mx-auto flex flex-col justify-center items-center"
		style=" background-image: url('https://ggheaven.com/wp-content/uploads/2022/04/World-Of-Warships.jpg);"
	>
		<form class="flex gap-2">
			<Search size="md" />
			<Button class="!p-2.5">Search</Button>
		</form>
	</div>
</section>

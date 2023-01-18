<script>
	import Logo from '../lib/images/logo.png'
</script>

<svelte:head>
	<script src="https://cdn.tailwindcss.com"></script>
</svelte:head>

<div class="app">
	<nav class="bg-gray-100 p-3 flex justify-start">
		<a href="/"><img src={Logo} class="w-30 h-24" alt="logo"></a>
		<a class="text-black p-3 m-6 text-xl" href="/introduce">소개</a>
		<a class="text-black p-3 m-6 text-xl" href="/inform">공지사항</a>
		<a class="text-black p-3 m-6 text-xl" href="https://discord.gg/cYC3vsxmTF" target="_blank">입사하기</a>
		<a class="text-black p-3 m-6 text-xl" href="https://www.youtube.com/@cednumetro" target="_blank">Youtube</a>
	</nav>
	<main class="p-5">
		<slot />
	</main>
</div>
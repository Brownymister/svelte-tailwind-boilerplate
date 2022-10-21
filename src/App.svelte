<script>
  import svelteLogo from './assets/svelte.svg'
</script>

<main>
    <div class="m-16 flex flex-row items-center justify-center">
    <a href="https://tailwindcss.com"> 
        <img class="w-20 m-8" src="/tailwind.svg" alt="Tailwind Logo" />
    </a>
    <a href="https://svelte.dev"> 
        <img class="w-20 m-4" src={svelteLogo} alt="Svelte Logo" />
    </a>

    </div>
    <h1 class="font-bold text-5xl text-gray-400 text-center">Tailwind + Svelte</h1>

    <p class="text-gray-400 text-lg text-center m-16">Try edit <span class="rounded-md bg-gray-800 p-1">./src/App.svelte</span></p>

</main>

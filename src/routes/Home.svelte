<script>
    import svelteLogo from '../assets/svelte.svg'
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

    <p class="text-gray-400 text-lg text-center m-16">Start edit <span class="rounded-md bg-gray-800 p-1">./src/App.svelte</span></p>
    
    <div class="m-4 text-gray-400 flex flex-row items-center justify-center">
        <div class="p-6 max-w-sm rounded-lg border shadow-md bg-gray-800 border-gray-700">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-200">Tailwindcss Documantation</h5>
            <p class="mb-3 font-normal text-gray-400">See the Tailwind documentation for more classes to add to your code.</p>
            <a href="https://tailwindcss.com" class="inline-flex items-center text-blue-600 hover:underline">
                Forward me
                <svg class="ml-2 w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M11 3a1 1 0 100 2h2.586l-6.293 6.293a1 1 0 101.414 1.414L15 6.414V9a1 1 0 102 0V4a1 1 0 00-1-1h-5z"></path><path d="M5 5a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2v-3a1 1 0 10-2 0v3H5V7h3a1 1 0 000-2H5z"></path></svg>
            </a>
        </div>

    </div>

</main>

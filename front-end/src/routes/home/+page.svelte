<script>
    import PotatoClassCard from "../../components/PotatoClassCard.svelte";
    let y;
</script>


<section class="flex flex-col w-screen h-screen bg-red-50">
    <div class="w-full h-[80px] bg-blue-400">
    </div>
    <div class="grid gap-2 grid-cols-4 auto-rows-fr w-full bg-yellow-400 p-2"> 
        {#each Array(100) as x} 
            <div class="bg-indigo-400 w-full h-96">{x}</div>
        {/each}
    </div>
</section>
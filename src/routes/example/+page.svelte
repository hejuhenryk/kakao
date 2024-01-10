<script>
    import task from "../../example.png";
    import Team1 from "../../components/Example/Team1.svelte";
    import Team2 from "../../components/Example/Team2.svelte";
    import Team3 from "../../components/Example/Team3.svelte";
    import Team4 from "../../components/Example/Team4.svelte";
    import Team5 from "../../components/Example/Team5.svelte";
    import Team6 from "../../components/Example/Team6.svelte";
    import Team7 from "../../components/Example/Team7.svelte";
    import Team8 from "../../components/Example/Team8.svelte";
    import Team9 from "../../components/Example/Team9.svelte";
    import Team10 from "../../components/Example/Team10.svelte";
    import Team11 from "../../components/Example/Team11.svelte";
    import Team12 from "../../components/Example/Team12.svelte";
    import Team13 from "../../components/Example/Team13.svelte";
    import Team14 from "../../components/Example/Team14.svelte";
    import Team15 from "../../components/Example/Team15.svelte";
    $: columns = 4;
    
</script>


<main class="grid grid-cols-3" style="grid-template-columns: repeat({columns}, minmax(0, 1fr))">
    <div class="relative">
        <div class="absolute flex gap-4 top-2 left-2">
            <button class="flex w-6 h-6 justify-center items-center p-0  rounded-full bg-lime-700 text-base/[1rem]" on:click={()=>columns += 1 } >+</button>
            <button class="flex w-6 h-6 justify-center items-center p-0  rounded-full bg-lime-700 text-base/[1rem]" on:click={()=>columns -= 1 } >-</button>
        </div>
        <h1 class="text-center text-fuchsia-600 text-2xl font-bold absolute opacity-50 top-3/4 left-1/2 -translate-x-1/2  -translate-y-1/2 bg-white/30">Example</h1>
        <img src={task} alt="" />
    </div>
    <a href="/example/1" class="border border-3 border-fuchsia-500">
        <Team1 />
    </a>
    <a href="/example/2" class="border border-3 border-fuchsia-500">
        <Team2 />
    </a>
    <a href="/example/3" class="border border-3 border-fuchsia-500">
        <Team3 />
    </a>
    <a href="/example/4" class="border border-3 border-fuchsia-500">
        <Team4 />
    </a>
    <a href="/example/5" class="border border-3 border-fuchsia-500">
        <Team5 />
    </a>
    <a href="/example/6" class="border border-3 border-fuchsia-500">
        <Team6 />
    </a>
    <a href="/example/7" class="border border-3 border-fuchsia-500">
        <Team7 />
    </a>
    <a href="/example/8" class="border border-3 border-fuchsia-500">
        <Team8 />
    </a>
    <a href="/example/9" class="border border-3 border-fuchsia-500">
        <Team9 />
    </a>
    <a href="/example/10" class="border border-3 border-fuchsia-500">
        <Team10 />
    </a>
    <a href="/example/11" class="border border-3 border-fuchsia-500">
        <Team11 />
    </a>
    <a href="/example/12" class="border border-3 border-fuchsia-500">
        <Team12 />
    </a>
    <a href="/example/13" class="border border-3 border-fuchsia-500">
        <Team13 />
    </a>
    <a href="/example/14" class="border border-3 border-fuchsia-500">
        <Team14 />
    </a>
    <a href="/example/15" class="border border-3 border-fuchsia-500">
        <Team15 />
    </a>
</main>

<style>
    main > * {
        overflow: scroll;
        aspect-ratio: 5/3;
    }
</style>
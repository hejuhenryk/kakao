<script>
    import task from "../../page2.png";
    import Team1 from "../../components/Task2/Team1.svelte";
    import Team2 from "../../components/Task2/Team2.svelte";
    import Team3 from "../../components/Task2/Team3.svelte";
    import Team4 from "../../components/Task2/Team4.svelte";
    import Team5 from "../../components/Task2/Team5.svelte";
    import Team6 from "../../components/Task2/Team6.svelte";
    import Team7 from "../../components/Task2/Team7.svelte";
    import Team8 from "../../components/Task2/Team8.svelte";
    import Team9 from "../../components/Task2/Team9.svelte";
    import Team10 from "../../components/Task2/Team10.svelte";
    import Team11 from "../../components/Task2/Team11.svelte";
    import Team12 from "../../components/Task2/Team12.svelte";
    import Team13 from "../../components/Task2/Team13.svelte";
    import Team14 from "../../components/Task2/Team14.svelte";
    import Team15 from "../../components/Task2/Team15.svelte";
    $: columns = 4;
    
</script>


<main class="grid grid-cols-3" style="grid-template-columns: repeat({columns}, minmax(0, 1fr))">
    <div class="relative">
        <div class="absolute flex gap-4 top-2 left-2">
            <button class="flex w-6 h-6 justify-center items-center p-0  rounded-full bg-lime-700 text-base/[1rem]" on:click={()=>columns += 1 } >+</button>
            <button class="flex w-6 h-6 justify-center items-center p-0  rounded-full bg-lime-700 text-base/[1rem]" on:click={()=>columns -= 1 } >-</button>
        </div>
        <h1 class="text-center text-fuchsia-600 text-2xl font-bold absolute opacity-50 top-3/4 left-1/2 -translate-x-1/2  -translate-y-1/2">Task 2</h1>
        <img src={task} alt="" />
    </div>
    <a href="/task2/1" class="border border-3 border-fuchsia-500">
        <Team1 />
    </a>
    <a href="/task2/2" class="border border-3 border-fuchsia-500">
        <Team2 />
    </a>
    <a href="/task2/3" class="border border-3 border-fuchsia-500">
        <Team3 />
    </a>
    <a href="/task2/4" class="border border-3 border-fuchsia-500">
        <Team4 />
    </a>
    <a href="/task2/5" class="border border-3 border-fuchsia-500">
        <Team5 />
    </a>
    <a href="/task2/6" class="border border-3 border-fuchsia-500">
        <Team6 />
    </a>
    <a href="/task2/7" class="border border-3 border-fuchsia-500">
        <Team7 />
    </a>
    <a href="/task2/8" class="border border-3 border-fuchsia-500">
        <Team8 />
    </a>
    <a href="/task2/9" class="border border-3 border-fuchsia-500">
        <Team9 />
    </a>
    <a href="/task2/10" class="border border-3 border-fuchsia-500">
        <Team10 />
    </a>
    <a href="/task2/11" class="border border-3 border-fuchsia-500">
        <Team11 />
    </a>
    <a href="/task2/12" class="border border-3 border-fuchsia-500">
        <Team12 />
    </a>
    <a href="/task2/13" class="border border-3 border-fuchsia-500">
        <Team13 />
    </a>
    <a href="/task2/14" class="border border-3 border-fuchsia-500">
        <Team14 />
    </a>
    <a href="/task2/15" class="border border-3 border-fuchsia-500">
        <Team15 />
    </a>
</main>

<style>   
 main > * {
    overflow: scroll;
    aspect-ratio: 5/3;
}
</style>
<script>
    import task from "../../page1.png";
    import Team1 from "../../components/Task1/Team1.svelte";
    import Team2 from "../../components/Task1/Team2.svelte";
    import Team3 from "../../components/Task1/Team3.svelte";
    import Team4 from "../../components/Task1/Team4.svelte";
    import Team5 from "../../components/Task1/Team5.svelte";
    import Team6 from "../../components/Task1/Team6.svelte";
    import Team7 from "../../components/Task1/Team7.svelte";
    import Team8 from "../../components/Task1/Team8.svelte";
    import Team9 from "../../components/Task1/Team9.svelte";
    import Team10 from "../../components/Task1/Team10.svelte";
    import Team11 from "../../components/Task1/Team11.svelte";
    import Team12 from "../../components/Task1/Team12.svelte";
    import Team13 from "../../components/Task1/Team13.svelte";
    import Team14 from "../../components/Task1/Team14.svelte";
    import Team15 from "../../components/Task1/Team15.svelte";
</script>

<main class="grid grid-cols-4">
    <div class="relative">
        <h1 class="text-center text-fuchsia-600 text-2xl font-bold absolute opacity-50 top-3/4 left-1/2 -translate-x-1/2  -translate-y-1/2">Task 1</h1>
        <img src={task} alt="" />
    </div>
    <a href="/task1/1" class="border border-3 border-fuchsia-500">
        <Team1 />
    </a>
    <a href="/task1/2" class="border border-3 border-fuchsia-500">
        <Team2 />
    </a>
    <a href="/task1/3" class="border border-3 border-fuchsia-500">
        <Team3 />
    </a>
    <a href="/task1/4" class="border border-3 border-fuchsia-500">
        <Team4 />
    </a>
    <a href="/task1/5" class="border border-3 border-fuchsia-500">
        <Team5 />
    </a>
    <a href="/task1/6" class="border border-3 border-fuchsia-500">
        <Team6 />
    </a>
    <a href="/task1/7" class="border border-3 border-fuchsia-500">
        <Team7 />
    </a>
    <a href="/task1/8" class="border border-3 border-fuchsia-500">
        <Team8 />
    </a>
    <a href="/task1/9" class="border border-3 border-fuchsia-500">
        <Team9 />
    </a>
    <a href="/task1/10" class="border border-3 border-fuchsia-500">
        <Team10 />
    </a>
    <a href="/task1/11" class="border border-3 border-fuchsia-500">
        <Team11 />
    </a>
    <a href="/task1/12" class="border border-3 border-fuchsia-500">
        <Team12 />
    </a>
    <a href="/task1/13" class="border border-3 border-fuchsia-500">
        <Team13 />
    </a>
    <a href="/task1/14" class="border border-3 border-fuchsia-500">
        <Team14 />
    </a>
    <a href="/task1/15" class="border border-3 border-fuchsia-500">
        <Team15 />
    </a>
</main>

<style>
    main > * {
        max-height: 40rem;
        overflow: hidden;
        aspect-ratio: 5/3;
    }
</style>
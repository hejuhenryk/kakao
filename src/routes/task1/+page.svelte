<script>
    import Team1 from "../../components/Task1/Team1.svelte";
    import Team2 from "../../components/Task1/Team2.svelte";
</script>

<main class="grid grid-cols-4">
    <h1>task 1</h1>
    <a href="/task1/1" class="border border-3 border-fuchsia-500">
        hello
        <Team1 />
    </a>
    <a href="/task1/2" class="border border-3 border-fuchsia-500">
        <Team2 />
    </a>
</main>

<style>
    main > * {
        max-height: 40rem;
        overflow: hidden;
        aspect-ratio: 5/3;
    }
</style>
<script lang="ts">
    import Team1 from "../../../components/Task1/Team1.svelte"
    import Team2 from "../../../components/Task1/Team2.svelte"

    import { page } from '$app/stores';
    const team = $page.params.team;
</script>

<!-- Routing works now :) -->
{#if team === "1"}
    <Team1 />
{/if}
{#if team === "2"}
    <Team2 />
{/if}
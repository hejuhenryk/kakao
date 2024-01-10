<script lang="ts">
    import { page } from '$app/stores';
    const team = $page.params.team;
    import Team1 from "../../../components/Task1/Team1.svelte"
    import Team2 from "../../../components/Task1/Team2.svelte"
	import Team3 from "../../../components/Task1/Team3.svelte";
    import Team4 from "../../../components/Task1/Team4.svelte";
    import Team5 from "../../../components/Task1/Team5.svelte";
    import Team6 from "../../../components/Task1/Team6.svelte";
    import Team7 from "../../../components/Task1/Team7.svelte";
    import Team8 from "../../../components/Task1/Team8.svelte";
	import Team9 from "../../../components/Task1/Team9.svelte";
	import Team10 from "../../../components/Task1/Team10.svelte";
	import Team11 from "../../../components/Task1/Team11.svelte";
	import Team12 from "../../../components/Task1/Team12.svelte";
	import Team13 from "../../../components/Task1/Team13.svelte";
	import Team14 from "../../../components/Task1/Team14.svelte";
	import Team15 from "../../../components/Task1/Team15.svelte";
</script>

<!-- Routing works now :) -->
{#if team === "1"}
    <Team1 />
{/if}
{#if team === "2"}
    <Team2 />
{/if}
{#if team === "3"}
    <Team3 />
{/if}
{#if team === "4"}
    <Team4 />
{/if}
{#if team === "5"}
    <Team5 />
{/if}
{#if team === "6"}
    <Team6 />
{/if}
{#if team === "7"}
    <Team7 />
{/if}
{#if team === "8"}
    <Team8 />
{/if}
{#if team === "9"}
    <Team9 />
{/if}
{#if team === "10"}
    <Team10 />
{/if}
{#if team === "11"}
    <Team11 />
{/if}
{#if team === "12"}
    <Team12 />
{/if}
{#if team === "13"}
    <Team13 />
{/if}
{#if team === "14"}
    <Team14 />
{/if}
{#if team === "15"}
    <Team15 />
{/if}
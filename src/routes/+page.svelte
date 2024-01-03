<script>
	import Team1 from "../components/Team1.svelte";
	import Team2 from "../components/Team2.svelte";
	import Team3 from "../components/Team3.svelte";
	import Team4 from "../components/Team4.svelte";
	import Team5 from "../components/Team5.svelte";
    import image1 from '../page1.png';
</script>

<p class="text-3xl mb-10">https://prod.liveshare.vsengsaas.visualstudio.com/join?2C328A8A02108EAE94F6D433D6F1D5A51F76</p>
<p class="text-3xl mb-10">https://d7d3-195-1-85-189.ngrok-free.app</p>

<main class="grid grid-cols-2">
    <div class="grid grid-cols-2 gap-2 border border-3 border-fuchsia-500">
        <Team1 />
        <img src={image1} alt="" />
    </div>
    <div class="grid grid-cols-2 gap-2 border border-3 border-fuchsia-500">
        <Team2 />
        <img src={image1} alt="" />
        
    </div>
    <div class="grid grid-cols-2 gap-2 border border-3 border-fuchsia-500">
        <Team3 />
        <img src={image1} alt="" />
        
    </div>
    <div class="grid grid-cols-2 gap-2 border border-3 border-fuchsia-500">
        <Team4 />
        <img src={image1} alt="" />
        
    </div>
    <div class="grid grid-cols-2 gap-2 border border-3 border-fuchsia-500">
        <Team5 />
        <img src={image1} alt="" />

    </div>
</main>

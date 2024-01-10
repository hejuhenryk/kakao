<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>
<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&display=swap" rel="stylesheet">
</svelte:head>

<section class="flex flex-col items-center">
    <!-- change html inside section -->
    <div class="p-4 flex gap-3">
        <h1 class="font-serif">Team 1</h1>
        <h2 class="font-sans">Team 1</h2>
        <h2 class="font-mono">Team 1</h2>
        <h3 class="google-font">Team 1</h3>
    </div>
    <!-- You can use tailwind -->
    <p class="text-red-500">Example <span class="font-bold">text</span></p>
    <img src={bilde1} alt="" class="w-[80%]" />
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }

    .google-font {
        font-family: 'Bungee Spice', sans-serif;
    }
</style>
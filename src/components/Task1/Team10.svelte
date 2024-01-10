<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <h1>Team 10</h1>
    <!-- You can use tailwind -->
    <p class="text-red-500">Example <span class="font-bold">text</span></p>
    <img src={bilde1} alt="" />
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }
</style>
<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section class="flex flex-col items-center">
    <!-- change html inside section -->
    <h1>Team 1</h1>
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

</style>
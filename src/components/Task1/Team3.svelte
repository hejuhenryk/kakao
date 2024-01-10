<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <div class=" mx-[20%] ">
    <!-- top row -->
        <div flex flex-row justify-between mb-[40px]>
            <div>
                <p class="mr-1">THREADS</p>
                <p class="mr-1">INSTAGRAM</p>
                <p>LINKEDIN</p>
            </div>
            <h3>ERIK©</h3>
            <div>
                <p class="mr-1">WORKS</p>
                <p class="mr-1">ABOUT</p>
                <p>CONTACT</p>
            </div>
        </div>

        <h1 class="text-center mx-[20%] mb-6">CREATIVE DEVELOPER PORTFOLIO</h1>

        <p class="mb-4 ">I PASSIONATELY CRAFT CAPTIVATING VISUALS, BLENDING ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING ORIGINALITY WITH PRECISION AND FLAIR.</p>
        
        <p class="p-[16px] bg-white mb-[40px]">HELLO@ERIKLINDSTROM.COM</p>

        <div class="flex flex-row justify-between">
            <p>SELECTED WORK</p>
            <p>(2021-PRESENT)</p>
        </div>

        <img class="rounded-md" src={bilde1} alt="Mørk bil i mørket" />
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        font-family: 'Inter Tight', sans-serif;
        color: black;
        background-color: "#E8E8E8";
    }
</style>
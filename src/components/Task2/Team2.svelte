<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section class="grid">
    <nav class="flex justify-between items-center mx-6">
        <span class="flex gap-2">Visit<svg width="32" height="23" viewBox="0 0 32 23" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="32" height="23" fill="url(#pattern0)"/>
            <defs>
            <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_84_232" transform="scale(0.03125 0.0434783)"/>
            </pattern>
            <image id="image0_84_232" width="32" height="23" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>Norway</span>
        <div class="flex gap-2"><span>Offers</span>
        <span>Favorite</span>
        <span>Search</span>
        <span>Menu</span></div>
        </nav>
    <div class="relative">
        <img src={bilde1} alt="" class="w-full"/>
        <div class="flex flex-col justify-center absolute top-1/2 left-1/2 translate-y-1/2 translate-x-1/2 translate-50 items-center gap-3 bg-white/30 rounded-md">
            <h2 class="text-center font-bold text-3xl">Opplev Norge</h2>
            <strong>Eventyr, familieferie eller en romantisk helg?</strong>
            <p>Norge er fullt av spennende opplevelser! Planlegg turen, få inspirasjon og supre tips fra lokalkjente.</p>
        </div>
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }
</style>
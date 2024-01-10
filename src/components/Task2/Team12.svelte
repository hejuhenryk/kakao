<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section class="flex flex-col items-center h-screen">
    <ul class="flex justify-between">
        <div>
            <li class="mx-6 font-bold">Visit Norway</li>
        </div>

        <div class="flex">
            <li class="mx-6 font-bold">Offers</li>
            <li class="mx-6 font-bold">Favorite</li>
            <li class="mx-6 font-bold">Search</li>
            <li class="mx-6 font-bold">Menu</li>

        </div>

    </ul>
    <div id="shrek" class="size-max flex flex-col">
        <div class="pt-8 px-4 bg-slate-100 font-bold py-2 rounded-lg flex flex-col">
            <p class="text-4xl mt-2 font-bold">Opplev Norge</p>
            <p class="text-2xl mt-1 font-bold">Eventyr, familieferie eller en romantisk helg</p>
            <p class="text-2xl mt-1">Norge er fullt av spennende opplevelser!Planlegg turen, få</p>
            <p class="text-2xl mt-1">inspirasjon og supre tips fra lokalkjente</p>

        </div>
    </div>
    
    <div class="pt-1 px-2 bg-white font-bold py-2 rounded-lg flex flex-row">
        <div class="flex flex-col">
            <p class="text-gray">Denne nettsiden bruker informasjonkapsler for å tilpasse annonser og male og optimalisere ytelsen. vi deler</p>
            <p class="text-gray">informasjon om din bruk av nettsiden med våre samarbeidspartnere. Ved å fortsette å bruke nettsiden, godtar du vår</p>
            <p class="text-gray">personvern- og sikkerhetspolicy. Vennligst bekreft at du samtykker til vår bruk av informasjonskapsler</p>
            <p class="underline text-blue">Personvern- og sikkerhetsvilkår</p>


        </div>
        <div class="flex flex-col pt-2">
            <button class="bg-blue text-white font-bold py-2 px-4 rounded-full mt-2"> Ja, det er greit!</button>
            <button class="bg-blue text-white font-bold py-2 px-4 rounded-full mt-2"> Kun nødvendige</button>
            <button class="bg-white text-blue font-bold py-2 px-4 rounded-full mt-2 border-blue"> Rediger innstillinger</button>

        </div>

    </div>


</section>

<style>
    /** Input custom css here */
    #shrek {
     background-image: url("./bilde1.png");
    }
</style>
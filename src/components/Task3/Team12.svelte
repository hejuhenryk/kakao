<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section class="flex flex-col items-center h-screen">
    <ul class="flex justify-between">
        <div class="flex flex-col">
            <li class="mx-6 font-bold">Wikipedia</li>
            <li class="mx-6 font-bold">Den frie encyklopedi</li>
        </div>
        <div>
            <li class="mx-6">Søk i Wikipedia</li>
            <li>søk</li>
        </div>
        <div>
            <li class="mx-6 font-bold">Opprett konto</li>
            <li class="mx-6 font-bold">Logg inn</li>
            <li class="mx-6 font-bold">...</li>
        </div>

    </ul>
    <div class="flex w-full">
        <div class="flex flex-col m-1 w-1/5">
                <div class="flex">
                    <p class="font-bold text-black">Innhold</p>
                    <p class="font-bold text-black bg-slate-700 pl-2 px-4 rounded">skjul</p>
                </div>
                <p class="font-bold text-black mt-1">(Til Toppen)</p>
                <p class="font-light text_slate-600 mt-1">_______________________________</p>
                <p class="font-bold text-blue mt-1">Bruk</p>
                <p class="font-bold text-blue mt-1">Produksjon</p>
                <p class="font-bold text-blue mt-1">Innholdsstoffer i kakao</p>
                <p class="font-bold text-blue mt-1">kakao og dyr</p>
                <p class="font-bold text-blue mt-1">se også</p>
                <p class="font-bold text-blue mt-1">referanser</p>
                <p class="font-bold text-blue mt-1">eksterne lenker</p>
        </div>
        <div class="flex flex-col">
            <div class="flex justify-between">
                <p class="text-4xl"> Kakao</p>
                <p class="text-2xl"> 44 språk</p>
            </div>
            <div class="flex justify-between">
                <div>
                    <p>Artikkel</p>
                    <p class="text-blue">Diskusjon</p>
                </div>
                <div>
                    <p>Les</p>
                    <p>Rediger</p>
                                        <p>Rediger kilde</p>
                    <p>Vis historikk</p>
                    <p>Verktøy</p>
                </div>
            </div>
            <p class="text-blue">Artikkel på nynorsk</p>
            <p>Denne artikkelen handler om næringsmiddelet kakao. FOr drikk laget av dette, se kakao(drikk)</p>
        <div class="flex">
            <div class="flex flex-col">
                <div class="flex"><p class="text-3xl">Bruk</p><p class="text-blue">   [rediger | rediger kilde]</p></div>
                <p>Kakao blir benyttet i drikker, som for eksempel varm sjokolade og sjokolademelk, og til å</p>
                <p>lage sjokolade. Det er en vanlig ingrediens i forskjellige kaker, som sjokoladekake eller brownies.</p>
                <p>Som oftest tenker man på kakao i forbindelse med søte matvarer, men blant annet i meksikansk matlaging er det ikke uvanlig å bruke kakao som ingrediens uten</p>
                <p>sukker, som for eksempel i chiligryter.</p>
                <div class="flex"><p class="text-3xl">Produksjon</p><p class="text-blue">   [rediger | rediger kilde]</p></div>
                <p> Treet krever tropisk klima for å trives, altså cirka 20 grader nord og sør for ekvatoren. Største produsent i verden er Elfenbenskysten som står for over 1 million tonn av en totalproduksjon på vel 3 millioner tonn, altså en tredel. Andre betydelige produsenter er Indonesia, Ghana, Nigeria, Brasil, Kamerun og Ecuador. Det finnes tre hovedsorter av kakao: Forastero, Criollo, og Trinitario. Forastero står for 95% prosent av produksjonen, Criollo gir en bedre kvalitet, men lavere avkastning og er mer mottakelig for sykdommer og Trinitario er en hybrid av de to andre.</p>
            </div>
            <img src={bilde1} alt="" class="float-right w-8"/>

        </div>
        </div>

    </div>
</section>

<style>
    /** Input custom css here */
    p {
        margin-top: 1px;
    }
</style>
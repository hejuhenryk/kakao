<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <div class="mb-[30px] flex flex-row" >
        <p>🍔   </p>
        <p>🌍   </p>
        <img src="https://no.wikipedia.org/static/images/icons/wikipedia.png" alt="" />
        <input class="ml-[30px] mr[40px]" type="search" placeholder="🔍 Søk i wikipedia"/>
        <div class="text-blue">
            <p>Opprett konto  </p>
            <p>Logg inn  </p>
            <p class="font-bold">...</p>
        </div>

        <div id="content" class="flex flex-row gap-10">
            <div class="flex flex-column mt-5">
                <div class="font-bold">
                <p>Innhold</p>
               <p> (Til toppen) </p>
                </div>
                <div class="text-blue">
                    <p>Bruk</p>
                    <p>Produksjon</p>
                    <p>Innholdsstoffer i kakao</p>
                    <p>Kakao og dyr</p>
                    <p>Se også</p>
                    <p>Referanser</p>
                    <p>Eksterne lenker</p>
                </div>
            </div>

            <div id="innhold flex flex-column gap-4">
                <h1 class="text-xl">Kakao</h1>
                <hr class="solid">
                <div class="flex flex-row justify-between ">
                    <div class="flex flex-row ">
                <p class="underline"> Artikkel   </p>
                <p class="text-blue">Diskusjon</p>
                    </div>
                    <div class="flex flex-row ">
                <p class="underline"> Les </p>
                <p class="text-blue">  Rediger</p>
                <p class="text-blue">   Diskusjon</p>
                <p class="text-blue">   Historikk</p>
                <p class="">Verktøy</p>
                </div>
                </div>
                <hr class="solid">
                <p class="text-sm">Kakao er favorittdrikken til hele utviklerTEAM 5 hos Itera (Verdens beste IT selskap!!) og et næringsmiddel fremstilt av kakaotreet (Theobroma cacao). Dette blir dyrket i de tropiske delene av Mellom- og Sør-Amerika, Asia og Afrika. Carl von Linné gav treet navnet Teobroma: gudenes føde.</p>

                <h2 class="mt-3 text-lg">Bruk</h2>
                <hr class="solid">

                <p>Kakao blir benyttet i drikker, som for eksempel varm sjokolade og sjokolademelk, og til å lage sjokolade. Det er en vanlig ingrediens i forskjellige kaker, som sjokoladekake eller brownies. Som oftest tenker man på kakao i forbindelse med søte matvarer, men blant annet i meksikansk matlaging er det ikke uvanlig å bruke kakao som ingrediens uten sukker, som for eksempel i chiligryter.
                </p>

                <h2 class="mt-3 text-lg">Produksjon</h2>
                <hr class="solid">

                <p>Treet krever tropisk klima for å trives, altså cirka 20 grader nord og sør for ekvatoren. Største produsent i verden er Elfenbenskysten som står for over 1 million tonn av en totalproduksjon på vel 3 millioner tonn, altså en tredel. Andre betydelige produsenter er Indonesia, Ghana, Nigeria, Brasil, Kamerun og Ecuador. Det finnes tre hovedsorter av kakao: Forastero, Criollo, og Trinitario. Forastero står for 95% prosent av produksjonen, Criollo gir en bedre kvalitet, men lavere avkastning og er mer mottakelig for sykdommer og Trinitario er en hybrid av de to andre.

                    En del kakaopulver er også behandlet med en prosess som på engelsk kalles "dutch processing". Denne prosessen fjerner en del av bitterheten i kakaoen, og gjør den mildere i smaken og mørkere i fargen. Dette er noe av grunnlaget for den særegne smaken til kjekstyper som Oreo's, som benytter det som ofte kalles sort kakao, som altså er kakao som er mye behandlet på denne måten.</p>
                <h2 class="mt-3 text-lg">Innholdsstoffer i kakao</h2>
                <hr class="solid">

                <p>Over halvparten av kakao er fett (kakaofett) og cirka 12 % protein. Totalt er det antatt at kakao inneholder cirka 300 forskjellige stoffer, deriblant mye antioksidanter, og alkaloidene teobromin og koffein.
                </p>

                

            


            </div>

            <div class="bg-slate-100 p-3 mt-[60px]">

            <img id="kakao" src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Theobroma_cacao_-_K%C3%B6hler%E2%80%93s_Medizinal-Pflanzen-137.jpg" alt="" />
            <p class="">Kakaofrukt med frø (Köhlers Medizinal Pflanzen, 1887)</p>    
            </div>

        </div>


    </div>

</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }

    hr.solid {
        border-top: 2px solid #bbb;
    }

</style>
<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    
    <!-- You can use tailwind -->
    
    <header style="display: flex">
        <div>
            WikipediA
        </div>
        <div>
            Søk i Wikipedia
        </div>
        <div>
            Opprett konto
        </div>
    </header> 
    <div style="display: flex, width: 100%">
         
        <div style="flex-basis: 30%"> 
            <p> Innhold </p>
            <hr />
            <p> Til toppen </p>
            <a href="/f"> Bruk </a>
            <a href="/f"> Produksjon </a>
            <a href="/f"> Se også </a>
            <a href="/f"> Innholdsstoffer </a>
            <a href="/f"> Kakaor og dyr </a>
            <a href="/f"> Referanser </a>
            <a href="/f"> Eksterne lenker </a>

        </div>

        <div style="flex-basis: 70%, width: 100%"> 
            <div class="section-70"> 
                <h1> 
                    Kakao
                </h1>
                <hr />
                <p> 
                    Kakao er et næringsmiddel fremstilt av kakaotreet (Theobroma cacao). 
                    Dette blir dyrket i de tropiske delene av Mellom- og Sør-Amerika, Asia og Afrika. Carl von Linné gav treet navnet Teobroma: gudenes føde.
                </p>
                <br />
                <div> 
                    <h3> Bruk</h3>
                    <hr/>
                    <p> 
                        Kakao blir benyttet i drikker, som for eksempel varm sjokolade og sjokolademelk, og 
                        til å lage sjokolade. Det er en vanlig ingrediens i forskjellige kaker, som sjokoladekake eller brownies. Som oftest tenker man på kakao i forbindelse med søte matvarer, men blant annet i meksikansk 
                        matlaging er det ikke uvanlig å bruke kakao som ingrediens uten sukker, som for eksempel i chiligryter.
                    </p>
                    <br/>
                </div>
                <div> 
                    <h3> Produksjon</h3>
                    <hr/>
                    <p> 
                        Treet krever tropisk klima for å trives, altså cirka 20 grader nord og sør for ekvatoren. Største produsent i verden er Elfenbenskysten som står for over 1 million tonn av en totalproduksjon på vel 3 millioner tonn, altså en tredel. Andre betydelige produsenter er Indonesia, Ghana, 
                        Nigeria, Brasil, Kamerun og Ecuador. Det finnes tre hovedsorter av kakao: Forastero, Criollo, og Trinitario. Forastero står for 95% prosent av produksjonen, Criollo gir en bedre kvalitet, men lavere avkastning og er mer mottakelig for sykdommer og Trinitario er en hybrid av de to andre.
    
                        En del kakaopulver er også behandlet med en prosess som på engelsk kalles "dutch processing". 
                        Denne prosessen fjerner en del av bitterheten i kakaoen, og gjør den mildere i smaken og mørkere i fargen. Dette er noe av grunnlaget for den særegne smaken til kjekstyper som Oreo's, som benytter det som ofte kalles sort kakao, som altså er kakao som er mye behandlet på denne måten.
                    </p>
                    <br/>
                </div>
            </div>
            <div class="section-30">
                <img class="image" src="https://no.wikipedia.org/wiki/Kakao#/media/Fil:Theobroma_cacao_-_K%C3%B6hler%E2%80%93s_Medizinal-Pflanzen-137.jpg" alt="f"/>

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
    .section-30 {
        width: 30%;

    }
    .section-70 {
        width: 70%;
        

    }
    .image {
        max-width: 250px


    }
    a {
        color: blue;
    }

</style>
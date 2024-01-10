<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section style="display: flex; flex-direction: column">
    <!-- change html inside section -->
    <span>Team 13</span>
    <div id="header">
        <div>
            <span>☰ Wikipedia</span>
        </div>
        <div>
            <input type="text" placeholder="Søk i Wikipedia" />
            <button>Søk</button>
        </div>
        <div>
            <a href="">Opprett konto</a>
            <a href="">Logg inn</a>
            <span>•••</span>
        </div>
    </div>
    <div id="body" style="display: flex">
        <nav>
            <h1>&nbsp;</h1>
            <div><span><b>Innhold</b></span><button>skjul</button></div>
            <hr>
            <div><span><b>(Til toppen)</b></span></div>
            <div>
                <ul>
                    <li>Bruk</li>
                    <li>Produksjon</li>
                    <li>Innholdsstoffer i kakao</li>
                    <li>Kakao og dyr</li>
                    <li>Se også</li>
                    <li>Referanser</li>
                    <li>Eksterne lenker</li>
                </ul>
            </div>
        </nav>
        <div>
            <h1>Kakao</h1>
            <div style="display: flex">
                <div>
                    <p style="margin-left: 25px"><i>Denne artikkelen handler om næringsmiddelet kakao. For drikk laget av dette, se <a href="">kakao (drikk)</a>.</i></p>
                    <p>
                        <b>Kakao</b> er et <a href="https://google.com">næringsmiddel</a> fremstilt av <a href="https://google.com">kakaotreet</a> (Theobroma cacao). Dette blir dyrket i de tropiske delene av <a href="https://google.com">Mellom</a>- og <a href="https://google.com">Sør-Amerika</a>, <a href="https://google.com">Asia</a> og <a href="https://google.com">Afrika</a>. <a href="https://google.com">Carl von Linné</a> gav treet navnet Teobroma: gudenes føde. 
                    </p>
                    <h2>Bruk <span style="font-size: 0.8em">[ <a href="https://google.com">rediger</a> | <a href="https://google.com">rediger kilde</a> ]</span></h2>
                    <hr>
                    <p>
                        Kakao blir benyttet i <a href="https://google.com">drikker</a>, som for eksempel <a href="https://google.com">varm sjokolade</a> og <a href="https://google.com">sjokolademelk</a>, og til å lage <a href="https://google.com">sjokolade</a>. Det er en vanlig <a href="https://google.com">ingrediens</a> i forskjellige kaker, som sjokoladekake eller brownies. Som oftest tenker man på kakao i forbindelse med søte matvarer, men blant annet i meksikansk matlaging er det ikke uvanlig å bruke kakao som ingrediens uten sukker, som for eksempel i chiligryter. 
                    </p>
                    <h2>Produksjon <span style="font-size: 0.8em">[ <a href="https://google.com">rediger</a> | <a href="https://google.com">rediger kilde</a> ]</span></h2>
                    <hr>
                    <p>
                        Treet krever tropisk klima for å trives, altså cirka 20 grader nord og sør for <a href="https://google.com">ekvatoren</a>. Største produsent i verden er <a href="https://google.com">Elfenbenskysten</a> som står for over 1 million tonn av en totalproduksjon på vel 3 millioner tonn, altså en tredel. Andre betydelige produsenter er <a href="https://google.com">Indonesia</a>, <a href="https://google.com">Ghana</a>, <a href="https://google.com">Nigeria</a>, <a href="https://google.com">Brasil</a>, <a href="https://google.com">Kamerun</a> og <a href="https://google.com">Ecuador</a>. Det finnes tre hovedsorter av kakao: Forastero, Criollo, og Trinitario. Forastero står for 95% prosent av produksjonen, Criollo gir en bedre kvalitet, men lavere avkastning og er mer mottakelig for sykdommer og Trinitario er en <a href="https://google.com">hybrid</a> av de to andre. 
                    </p>
                </div>
                <div>
                    <div style="border: 1px solid #e9ebed; background-color: #f9fafb">
                        <img src={bilde1} alt="" width="250" height="361" />
                        <span>Kakaofrukt med frø (<i>Köhlers Medizinal Pflanzen</i>, 1887)</span>
                    </div>
                </div>
            <div>
        </div>
    </div>
</section>

<style>
    section {
        background-color: white;
    }

    ul li {
        list-style-type: none;
    }
</style>
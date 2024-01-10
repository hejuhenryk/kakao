<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <h1 class="rainbow-text">Team 6</h1>

<nav>
    <!-- <h3>Wikipedia</h3> -->
    <img width="70" src="https://no.wikipedia.org/static/images/icons/wikipedia.png" alt="" />
    <img width="150" src="https://no.wikipedia.org/static/images/mobile/copyright/wikipedia-wordmark-en.svg" alt="" />
    <div class="flex-spacer"></div>
    <input class="search" type="text" placeholder="Søk i Wikipedia" />
    <button class="search-button">Søk</button>
    <div class="flex-spacer"></div>
    <a href="/">Opprett konto</a>
    <a href="/">Logg inn</a>
</nav>

<main class="flex-container">
    <div class="left">
        <h3 style="font-weight: bold; font-family: sans-serif;">Innhold</h3>
        <p style="font-weight: bold;">(Til toppen)</p>
        <div><a href="/">en link</a></div>
        <div><a href="/">en link</a></div>
    </div>
    <div class="middle">
        <h1 class="kakao">Kakao</h1>
        <section style="padding-bottom: 15px;">
            <i style="padding-bottom: 15px;">Denne artikkelen handler om næringsmiddelet kakao. For drikk laget av dette, se kakao (drikk).</i>
            
            <p>Kakao er et næringsmiddel fremstilt av kakaotreet (Theobroma cacao). Dette blir dyrket i de tropiske delene av Mellom- og Sør-Amerika, Asia og Afrika. Carl von Linné gav treet navnet Teobroma: gudenes føde.</p>
        </section>
        <section style="padding-bottom: 15px;">
            <h2>Bruk</h2>
            <p>
                Kakao blir benyttet i drikker, som for eksempel varm sjokolade og sjokolademelk, og til å lage sjokolade. Det er en vanlig ingrediens i forskjellige kaker, som sjokoladekake eller brownies. Som oftest tenker man på kakao i forbindelse med søte matvarer, men blant annet i meksikansk matlaging er det ikke uvanlig å bruke kakao som ingrediens uten sukker, som for eksempel i chiligryter.
            </p>
        </section>
        <section style="padding-bottom: 15px;">
            <h2>Produksjon</h2>
            <p>
                Treet krever tropisk klima for å trives, altså cirka 20 grader nord og sør for ekvatoren. Største produsent i verden er Elfenbenskysten som står for over 1 million tonn av en totalproduksjon på vel 3 millioner tonn, altså en tredel. Andre betydelige produsenter er Indonesia, Ghana, Nigeria, Brasil, Kamerun og Ecuador. Det finnes tre hovedsorter av kakao: Forastero, Criollo, og Trinitario. Forastero står for 95% prosent av produksjonen, Criollo gir en bedre kvalitet, men lavere avkastning og er mer mottakelig for sykdommer og Trinitario er en hybrid av de to andre.
            </p>
        </section>
    </div>
    <div class="right">
        <img src={bilde1} alt="" />
    </div>
</main>

</section>

<style>
    a {
        padding: 15px;
    }
    .kakao {
        font-family: serif;
    }
    h1, h2, h3, h4 {
        font-family: serif;
    }
    .middle {
        padding: 30px;
        width: 600px;
    }
    .left {
        width: 200px;
        padding: 40px;
    }
    main {
        margin-top: 40px;
    }
    .flex-container {
        width: 100%;
        display: flex;
        align-items: center;
    }
    .search-button {
        padding: 15px;
        font-weight: bold;
    }
    .search {
        width: 400px;
        padding: 15px;
        margin-top: 15px;
        margin-bottom: 15px;
    }
    .flex-spacer {
        flex-grow: 1;
    }
    nav {
        width: 100%;
        display: flex;
        align-items: center;
    }
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
        font-family: sans-serif;
    }

    .rainbow-text {
        font-family: arial black;
        font-size: 35px;
        background-image: 
            linear-gradient(to right, red,orange,yellow,green,blue,indigo,violet); 
        -webkit-background-clip: text;
        background-clip: text;
        -webkit-text-fill-color: transparent;  
        animation: move 60s linear infinite;
    }
    
    @keyframes move {
        to {
            background-position: 4500vh;
        }
    }
</style>
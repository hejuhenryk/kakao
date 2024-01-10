<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <div class="header">
        <div class="hamburger">🍔</div>
        <div class="logo">🌐</div>
        <div class="title">
            <div class="title-text">WikipediA</div>
            <div class="title-subtitle">Den frie encyklopedi</div>
        </div>
        <div class="search-container">
            <input type="search" class="search" placeholder="🔎 Søk i Wikipedia">
            <button>Søk</button>
        </div>
        <div class="separator"></div>
        <div class="actions">
            <a href="#">Opprett konto</a>&nbsp;&nbsp;&nbsp;
            <a href="#">Logg inn</a>&nbsp;&nbsp;&nbsp;
            ...
        </div>
    </div>
    <div class="main">
        <div class="menu">
            <div class="menu-header">
                Innhold (skjul)
            </div>
            <hr>
            <div class="to-top">(Til toppen)</div>
            <div><a>Bruk</a></div>
            <div><a>Produksjon</a></div>
            <div><a>Stem</a></div>
            <div><a>på</a></div>
            <div><a>lag</a></div>
            <div><a>5</a></div>
            <div><a>!</a></div>
            <div><a>!!</a></div>
            <div><a>!!!</a></div>
        </div>
        <div class="article">
            <div class="article-header">
                <h1>Kakao</h1>
                <div class="separator"></div>
                <div><a>开 44 språk</a></div>
            </div>
            <div class="article-sub-header">
                <div>Artikkel</div>
                <div><a>Diskusjon</a></div>
                <div class="separator"></div>
                <div>Les</div>
                <div><a>Rediger</a></div>
                <div><a>Rediger kilde</a></div>
                <div><a>Vis historikk</a></div>
                <div>Verktøy</div>
            </div>
            <div class="article-contents">
                <div class="article-left">
                    <div class="article-section">
                        Kakao er et <a>næringsmiddel</a> fremstilt av <a>kakaotreet</a> (Theobroma cacao). Dette blir dyrket i <br>
                        de tropiske delene av <a>Mellom-</a> og <a>Sør-Amerika</a>, <a>Asia</a> og <a>Afrika</a>. <a>Carl von Linné</a> gav treet <br>
                        navnet Teobroma: gudenes føde.
                    </div>
                    <div class="article-header">
                        <h2>Bruk</h2>
                        <hr>
                    </div>
                    <div class="article-section">
                        Kakao blir benyttet i <a>drikker</a>, som for eksempel <a>varm sjokolade</a> og <a>sjokolademelk</a>, og til å <br>
                        lage <a>sjokolade</a>. Det er en vanlig ingrediens i forskjellige kaker, som sjokoladekake eller <br>
                        brownies. Som oftest tenker man på kakao i forbindelse med søte matvarer, men blant <br>
                        annet i meksikansk matlaging er det ikke uvanlig å bruke kakao som ingrediens uten <br>
                        sukker, som for eksempel i chiligryter.
                    </div>
                    <div class="article-header">
                        <h2>Produksjon</h2>
                        <hr>
                    </div>
                    <div class="article-section">
                        Treet krever tropisk klima for å trives, altså cirka 20 grader nord og sør for ekvatoren. <br>
                        Største produsent i verden er Elfenbenskysten som står for over 1 million tonn av en <br>
                        totalproduksjon på vel 3 millioner tonn, altså en tredel. Andre betydelige produsenter er <br>
                        Indonesia, Ghana, Nigeria, Brasil, Kamerun og Ecuador. Det finnes tre hovedsorter av <br>
                        kakao: Forastero, Criollo, og Trinitario. Forastero står for 95% prosent av produksjonen, <br>
                        Criollo gir en bedre kvalitet, men lavere avkastning og er mer mottakelig for sykdommer <br>
                        og Trinitario er en hybrid av de to andre.
                    </div>
                </div>
                <div class="article-right">
                    <img src={bilde1} alt="" />
                </div>
            </div>
        </div>
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
        width: 100%;
    }

    .header {
        display: flex;
        flex-direction: row;
    }

    .search-container {
        display: flex;
        flex-direction: row;
        border: 1px solid gray;
    }

    .search-container button {
        border-left: 1px solid gray;
    }

    .separator {
        flex: 1 0 auto;
    }

    .main {
        display: flex;
        flex-direction: row;
    }

    .menu {
        margin-right: 20px;
    }
    
    .menu-header {
        font-weight: bold;
    }

    .article {
        flex: 1 0 auto;
    }

    .logo {
        font-size: 30px;
    }

    .article-header {
        display: flex;
        flex-direction: row;
    }

    .article-sub-header {
        display: flex;
        flex-direction: row;
    }
    
    .article-section {
        font-size: 12px;
    }

    .article-contents {
        display: flex;
        flex-direction: row;
    }

    .article-left {
        flex: 1 0 auto;
    }
    
    .article-right {
    }
</style>
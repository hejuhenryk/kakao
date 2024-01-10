<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <h1 class="rainbow-text">Team 6</h1>
    
    <nav>
        <h1>
            Visit 
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Flag_of_Norway.svg/1920px-Flag_of_Norway.svg.png" alt="norway" height="18px" />
            Norway
        </h1>
        <div class="flex-spacer"></div>
        <button>Offers</button>
        <button>Favorite</button>
        <button>Search</button>
        <button>Menu</button>
    </nav>

    <main>
        <img src={bilde1} alt="" class="bg-image"/>
        <div class="flex-container">
            <div class="flex-spacer"></div>
            <div class="flex-container-vertical">
                <div class="opplev">
                    <h1>Opplev Norge</h1>
                    <p><b>Eventyr, Familie eller en romantisk helg?</b></p>
                    <p>
                        Norge er fullt av spennende opplevelser! Planlegg turen, få
                        inspirasjon og supre tips fra lokalkjente.
                    </p>
                </div>
                <div class="cookies">
                    Denne nettsiden bruker informasjonskapsler for å tilpasse annonser og måle og optimalisere
                    ytelsen. Vi deler informasjon om din bruk av nettsiden med våre samarbeidspartnere. Ved å
                    fortsette å bruke nettsiden, godtar du vår personvern- og sikkerhetspolicy. Vennligst bekreft at
                    du samtykker til vår bruk av informasjonskapsler.
                </div>
            </div>
            <div class="flex-spacer"></div>
        </div>
    </main>

</section>

<style>
    .cookies {
        padding: 30px;
        background-color: white;
        border-radius: 5px;
        width: 1000px;
        color: #666666;
    }

    .opplev {
        margin-top: 300px;
        margin-bottom: 30px;
        padding: 30px;
        text-align: center;
        background-color: rgba(255, 255, 255, 0.7);
        border-radius: 5px;
        width: 500px;
    }
    .opplev > * {
        margin-bottom: 15px;
        text-align: center;
    }

    /** Input custom css here */
    section {
        color: black;
        background-color: white;
        font-family: sans-serif;
    }

    nav {
        background-color: none;
        width: 100%;
        display: flex;
        align-items: center;
    }

    nav > button {
        padding: 10px;
        margin: 10px;
        background: none;
        border: none;
        font-size: 8px;
    }

    .flex-spacer {
        flex-grow: 1;
    }

    .bg-image {
        position: absolute;
        z-index: -1;
        width:100%
    }

    .flex-container {
        width: 100%;
        display: flex;
        align-items: center;
    }

    .flex-container-vertical {
        display: flex;
        flex-direction: column;
        height: 100%;
    }

    main {
        width: 100%
    }

    .rainbow-text {
        font-family: arial black;
        font-size: 12px;
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
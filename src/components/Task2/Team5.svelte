<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <div class="header">
        <div class="header-visit">
            Visit 🇳🇴 Norway
        </div>
        <div class="header-separator"></div>
        <div class="header-actions">
            <div class="action-button">
                <div>X</div>
                <div>Offers</div>
            </div>
            <div class="action-button">
                <div>Y</div>
                <div>Favorite</div>
            </div>
            <div class="action-button">
                <div>Z</div>
                <div>Search</div>
            </div>
            <div class="action-button">
                <div>A</div>
                <div>Menu</div>
            </div>
        </div>
    </div>
    <div class="main" style="background-image: url({bilde1})">
        <div class="main-center">
            <div class="main-center-1">Opplev Norge</div>
            <div class="main-center-2">Eventyr, familieferie eller en romantisk helg?</div>
            <div class="main-center-3">Norge er fullt av spennende opplevelser! Planlegg turen, få inspirasjon og supre tips fra lokalkjente.</div>
        </div>
        <div class="cookie-box"> 
            <p>Denne nettsiden bruker informasjonskapsler for å tilpasse annonser og måle og optimalisere ytelsen. Vi deler <br>
                informasjon om din bruk av nettsiden med våre samarbeidspartnere. Ved å fortsette å bruke nettsiden, godtar du vår <br>
                personvern- og sikkerhetspolicy. Vennligst bekreft at du samtykker til vår bruk av informasjonskapsler. <br>
                Personvern- og sikkerhetspolicy
            </p>
            <div class="cookie-buttons">
            <button class="blue-button">Ja, det er greit!<button>
            <button class="blue-button">Kun nødvendige<button>
            <button class="white-button">Rediger innstillinger<button>
            <div>
        </div>
    </div>

</section>

<style>
    /** Input custom css here */
    section {
        font-family: sans-serif;
        color: black;
        background-color: white;
        width: 100%;
        height: 100%;
    }

    .header {
        display: flex;
        flex-direction: row;
        width: 100%;
        background-color: white;
        height: 70px;
    }
    
    .header-visit {
        font-size: 30px;
    }

    .header-separator {
        flex: 1 0 auto;
    }
    
    .header-actions {
        display: flex;
        flex-direction: row;
        font-size: 16px;
    }

    .action-button {
        display: flex;
        flex-direction: column;
    }

    .main {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .main-center {
        background-color: rgba(220, 220, 220, 0.9);
        display: flex;
        flex-direction: column;
        padding: 20px;
    }

    .main-center-1 {
        font-size: 48px;
        font-weight: bold;
    }

    .main-center-2 {
        font-size: 20px;
        font-weight: bold;
    }

    .main-center-3 {
        font-size: 20px;
    }

    .cookie-box {
        display: flex;
        flex-direction: row;
        background-color: white;
        margin: auto;
        border-radius: 5px;
    }

    .cookie-text {
        font-size: 10 px;
        color: gray;
    }

    .blue-button {
        background-color: blue;
        color: white;
        border-radius: 5px;
    }

    .white-button {
        background-color: white;
        color: blue;
        border-color: blue;
        border-radius: 5px;
        padding: 5px;
    }

    .cookie-buttoons {
        font-size: 20px;
        display: flex;
        flex-direction: column;
    }
    </style>
<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
    
</script>

<section>
    <!-- change html inside section -->

    <div class="flex flex-row justify-between p-[20px] bg-white mx-[40px]">
        <h1>Visit 🇳🇴 Norway</h1>
        <div class=" flex flex-row text-sm">
            <div>
            <p>Offers</p>
            </div>
            <div>
            <p>Favorite</p>
            </div>
            <p>Search</p>
            <div>
            <p>Menu</p>
            </div>
        </div>
    </div>
    <div id="bakgrunn" class="flex flex-column items-center justify-center">

        <div class=" items-center p-[20px] bg-opacity-70 bg-white justify-center">
            <h1>Opplev Norge</h1>
            <p><b>Eventyr, familieferie eller en romantisk helg?<b></p>
            <p>Norge er fullt av spennende opplevelser! Planlegg turen, <br>få inspirasjon og supre tips fra lokalkjente.</p>
        </div>
    </div>

    <div id="cookie" >
        <!--cookie accept box -->
        <div class="flex flex-row justify-between p-[30px]">
            <div class="flex flex-column gap-1">
                <p>Denne nettsiden bruker informasjonskapsler for å tilpasse annonser og måle og optimalisere ytelsen. Vi deler informasjon om din bruk av nettsiden med våre samarbeidspartnere. Ved å fortsette å bruke nettsiden, godtar du vår personvern- og sikkerhetspolicy. Vennligst bekreft at du samtykker til vår bruk av informasjonskapsler.</p>
                <a href="nrk.no">Personvern- og sikkerhetsvilkår</a>
            </div>

            <div class="flex flex-column gap-1">
                <button class="px-[20px] py-[8px] bg-[#41414] text-white">Accept</button>
                <button class="px-[20px] py-[8px] bg-blue text-white">Decline</button>
                <button class="px-[20px] py-[8px] bg-white text-blue">Rediger</button>
            </div>


    </div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }

    #bakgrunn {
        background-image: "./bilde2.png";
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        height: 600px;
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    #cookie {
        background-color: white;
        position: fixed;
        bottom: 0;
        width: 70%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
</style>
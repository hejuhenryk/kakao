<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <h1>Team 9</h1>
    <!-- You can use tailwind -->
    <p class="text-red-500">Example <span class="font-bold">text</span></p>
    <img src={bilde1} alt="" />

    <header> 
        <div class="logo"> 
            VISIT NORWAY
            
        </div>
        <div> 
            <a href="/offers"> 
                Offers
            </a>
            <a href="/fav"> 
                Favorite
            </a>
            <a href="/s"> 
                Search
            </a>
            <a href="/m"> 
                Menu
            </a>
        </div>
    </header>

    <div class="container"> 
        
        <div class="box"> 
            <h2> 
                Opplev Norge
            </h2>
            <br/> 
            <p> 
                <b> 
                    Eventyr, familieferie eller romantisk helg?
                </b>
            </p>
            <br/> 
            <p> 
                Norge er fullt av spennende opplevelser! 
                Planlegg turen, få inspirasjon og supre tips fra lokalkjente.
            </p>

        </div> 
    </div>
    
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-image: url("./task2.png") ;
        background-color: black;
        width: 100%;
    }
    .logo{
        max-height: 24px;
        width: auto;
        font-size: 30px;
    }

    header {
        color: black;
        background-color: white;
        height: 30px;

    }
    .container {
        height: 100%;
        width: 100%;
        display: flex;
        flex-direction: column;
        align-content: center;

    }
    .box {
        padding: 40%;
        color: white;
        opacity: 30%;
        border-radius: 15px;
    }
</style>
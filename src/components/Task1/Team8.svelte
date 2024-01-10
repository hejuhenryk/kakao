<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <div id="innhold">
    <!-- Navbar -->
    <div id="navbar">
        <div class="left">
            <div>THREADS</div>
            <div  style="margin-left: 20px;">INSTAGRAM</div>
            <div  style="margin-left: 20px;">LINKEDIN</div>
        </div>
        <div>ERIK(c)</div>
        <div class="right">
            <div>WORKS</div>
            <div  style="margin-left: 20px;">ABOUT</div>
            <div  style="margin-left: 20px;">CONTACT</div>
        </div>
    </div>
    <!-- Threads, Instagram, LinkedIn  -- Bruker/ERIK@ -- Works, About Contact -->
    <h1>CREATIVE DEVELOPER PORTFOLIO</h1>
    <!-- Brødtekst -->
<div style="margin-top: 40px; max-width: 400px">
    I PASSIONATELY CRAFT CAPTIVATING VISUALS, BELNDING ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING ORGINALITY WITH PRECISION AND FLAIR.
</div>
<!-- EPOST Hvit button avrundet-->
<button>HELLO@ERIKLINDSTROM.COM</button>
<!-- SELECTED WORK  (2021 - PRESENT)-->
<div style="margin-top: 40px;">
    <div class="left">SELECTED WORK</div>
    <div class="right">(2021 - PRESENT)</div>
</div>
    
    <img src={bilde1} alt="" />
</div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: rgb(232,232,232);
    }
    #innhold {
        width: 800px;
        margin: auto;
    }
    #navbar {
        height: 100px;
        text-align: center;
    }
    .left {
        float: left;
    }
    .right {
        float: right;
    }
    h1 {
        font-size: 100px;
        max-width: 500px;
    }
    button {
        background-color: white;
        border-radius: 15px;
        padding: 10px;
    }
    img {
        width: 800px;
        border-radius: 5px;
    }
</style>
<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <h1>Team 6</h1>
    <!-- You can use tailwind
    <p class="text-red-500">Example <span class="font-bold">text</span></p>
    <img src={bilde1} alt="" /> -->

    <nav>
        <div class="flex-spacer"></div>
        <button>THREADS</button>
        <button>INSTAGRAM</button>
        <button>LINKEDIN</button>
        <div class="flex-spacer"></div>
        <h3>ERIK&copy;</h3>
        <div class="flex-spacer"></div>
        <button>THREADS</button>
        <button>INSTAGRAM</button>
        <button>LINKEDIN</button>
        <div class="flex-spacer"></div>
    </nav>

    <main class="flex-container">
        <div class="flex-spacer"></div>
        <div class="inner-main-text">
            <heading>
                <h1>CREATIVE</h1>
                <h1>DEVELOPER</h1>
                <h1>PORTFOLIO</h1>
            </heading>
            <div>
                <p>I PASSIONATELY CRAFT CAPTIVATING VISUALS, BLENDING</p>
                <p>ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING</p>
                <p>ORIGINALITY WITH PRECISION AND FLAIR.</p>
            </div>
            <button class="button-round-solid">HELLO@ERIKLINDSTROM.COM</button>
            <div class="flex-container">
                <span>SELECTED WORK</span>
                <div class="flex-spacer"></div>
                <span>(2021 - PRESENT)</span>
            </div>
            <img src={bilde1} alt="bilde1" width="100px" />
        </div>
        <div class="flex-spacer"></div>
    </main>

</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        font-family: sans-serif;
        background-color: #444444;
    }

    nav {
        width: 100%;
        display: flex;
        align-items: center;
    }

    .flex-spacer {
        flex-grow: 1;
    }

    nav > button {
        padding: 10px;
        margin: 10px;
        font-weight: bold;
        background: none;
        border: none;
    }

    h1 {
        text-align: center;
        font-size: 60;
    }

    main > * {
        text-align: center;
    }

    .button-round-solid {
        border: none;
        border-radius: 30px;
        background-color: white;
        padding: 15px;
        margin: 15px;
        color: black;
        font-weight: bold;
    }

    .flex-container {
        width: 100%;
        display: flex;
        align-items: center;
    }

    .inner-main-text > * {
        margin-bottom: 20px;
    }
</style>
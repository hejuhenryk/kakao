<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <div class="main-container">
        <div class="main-left">
    
        </div>
        <div class="main-center">
            <div class="main-header">
                <div class="header-left">
                    <div>THREADS</div>
                    <div>INSTAGRAM</div>
                    <div>LINKEDIN</div>
                </div>
                <div class="header-divider"></div>
                <div class="header-center">
                    <div>ERIK©</div>
                </div>
                <div class="header-divider"></div>
                <div class="header-right">
                    <div>WORKS</div>
                    <div>ABOUT</div>
                    <div>CONTACT</div>
                </div>
            </div>
            <div class="logo">
                CREATIVE<br />
                DEVELOPER<br />
                PORTFOLIO
            </div>
            <div class="ingress">
                I PASSIONATELY CRAFT CAPTIVATING VISUALS, BLENDING<br />
                ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING<br />
                ORIGINALITY WITH PRECISION AND FLAIR.
            </div>
            <button class="main-button">HELLO@ERIKLINDSTROM.COM</button>
        </div>
        <p class="header-left"> SELECTED WORK</p>
        <p class="header-right">(2021-PRESENT)</p>
        <img src={bilde1} alt="" />
        <div class="main-right">
        </div>
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: lightgray;
        font-family: sans-serif;
        font-weight: bold;
    }

    .main-container {
        display: flex;
        flex-direction: row;
        width: 100%;
    }

    .main-left {
        width: 600px;
    }

    .main-right {
        width: 600px;
    }

    .main-header {
        width: 100%;
        display: flex;
        flex-direction: row;
        font-size: 15px;
    }

    .header-divider {
        flex: 1 0 auto;
    }

    .header-left, .header-right {
        display: flex;
        flex-direction: row;
        gap: 15px;
    }

    .logo {
        font-size: 100px;
    }
    
    .ingress {
        font-size: 15px;
    }

    .main-button {
        background-color: white;
        color: black;
        border-radius: 50%;
        font-size: 14px;
    }
</style>
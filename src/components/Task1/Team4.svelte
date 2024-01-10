<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<svelte:head>
    <link href="https://fonts.cdnfonts.com/css/roboto-condensed" rel="stylesheet">
</svelte:head>

<section class="body">
    <div class="container">

        meny lenkene

    </div>

    <div class="container">
        <h1 class="text-align-center">
            CREATIVE<br />
            DEVELOPER<br />
            PORTFOLIO
        </h1>
    </div>

    <div class="container text-align-center">
        I PASSIONATELY CRAFT CAPTIVATING VISUALS, BLENDING<br />
        ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING<br />
        ORIGINALITY WITH PRECISION AND FLAIR<br />
    </div>


    <div class="container center-content">
        <a>HELLO@ERIKLINDSTROM.COM</a>
    </div>

    <div class="container">

        work

        <img src={bilde1} alt="" />
    </div>



</section>

<style>
    /** Input custom css here */
    .body {
        font-family: 'Roboto Condensed', sans-serif;
        font-size: 16px;
    }

    .container {
        display: block;
        width: 100%;
    }

    .container + .container {
        margin-top: 32px;
    }

    .text-align-center {
        text-align: center;
    }

    h1 {
        font-size: 80px;
        font-weight: 700;
    }

    .center-content {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    a {
        padding: 20px;
        background-color: white;
        border-radius: 100%;
    }
</style>
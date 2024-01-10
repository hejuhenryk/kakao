<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>
<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href='https://fonts.googleapis.com/css?family=Inter Tight' rel='stylesheet'>
</svelte:head>

<section>
    <div id="header">
        <div>
            <span>THREADS</span>
            <span>INSTAGRAM</span>
            <span>LINKEDIN</span>
        </div>
        <div>
            <span><b>ERIK©</b></span>
        </div>
        <div>
            <span>WORKS</span>
            <span>ABOUT</span>
            <span>CONTACT</span>
        </div>
    </div>
    <div id="body">
        <h1>CREATIVE<br />DEVELOPER<br />PORTFOLIO<h1>
        <p>I PASSIONATELY CRAFT CAPTIVATING VISUALS, BLENDING</p>
        <p>ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING</p>
        <p>ORIGINALITY WITH PRECISION AND FLAIR.</p>
        <a href="mailto:hello@eriklindstrom.com">HELLO@ERIKLINDSTROM.COM</a>
        <div><span>SELECTED WORK</span><span>(2021 - PRESENT)</span></div>
        <img src={bilde1} alt="" />
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        display: flex;
        justify-content: center;
        background-color: #ebebeb;
        font-family: 'Inter Tight';
        width: 100vw;
    }

    #header {
        display: flex;
        width: 100vw;
        justify-content: space-between;
    }

    #body {
        width: 80vw;
    }

    h1 {
        margin-bottom: 20px;
    }

    p {
        margin-bottom: 0;
    }

    a {
        margin: 0;
        margin-top: 16px;
        border-radius: 30px;
        background-color: white;
    }

    img {
        display: block;
        width: 100%;
        text-decoration: none;
        pointer-events: none;
        cursor: pointer;
    }
</style>
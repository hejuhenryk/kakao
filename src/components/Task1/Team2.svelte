<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <header>
        <header-left>THREADS INSTAGRAM LINKEDIN</header-left>
        <header-right>ERIK©</header-right>
        <heaedr-middle>WORKS ABOUT CONTACT</heaedr-middle>
    </header>
    <title>CREATIVE DEVELOPER PORTFOLIO</title>
    <subtitle> stuff</subtitle>
    <button></button>
    <footnote>selected work (2021 - present)</footnote>
    <image>    <img src={bilde1} alt="" class="w-[100vw]" /></image>
    <h1>Team 2</h1>
    <!-- You can use tailwind -->
    <p class="text-red-500">Example <span class="font-bold">text</span></p>
    <img src={bilde1} alt="" class="w-[100vw]" />
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
        display: grid;
        grid-template-rows: 10vh 30vh 20vh 10vh 10vh 20vh;
        grid-template-columns: 25vw 50vw 25vw;
        grid-template-areas: "header header header"
         ". title ."
         ". subtitle ."
         " . button ."
         "footnote . footnote"
         "image image image";
    }

    header {
        grid-area: "header";
        grid-template-areas: "left middle right";
        font-weight: bold;
        align-content: center;
    }
    header-left {
        grid-area: "left";
    }
    header-right {
        grid-area: "right";
    }
        header-middle {
        grid-area: "middle";
    }
    title {
        grid-area: "title";
    }
    subtitle {
        grid-area: "subtitle"
    }
    button {
        grid-area: "button";
    }

    footnote {
        grid-area: "footnote";
    }

    image {
        grid-area: "image";
    }


    

</style>
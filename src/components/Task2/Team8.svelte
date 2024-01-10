<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <div id="navbar">
        <div class="left">
        <span>Visit</span>
        <img class="flagg" src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.norden.org%2Fen%2Finformation%2Fnorwegian-flag&psig=AOvVaw0jUvY8F8CqeA3GZq8pR3xC&ust=1704995390115000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCKDRlPiw04MDFQAAAAAdAAAAABAD" alt="">
         <span>Norway</span>
    </div>
    <div class="right">
        <span>Offers</span>
        <span>Favourite</span>
        <span>Search</span>
        <span>Menu</span>
    </div>
    <div id="innhold">
        <div class="on">
            <div style="font-size: 120px; font-weight: bold;">Opplev Norge</div>
            <div style="font-size: 60px;  font-weight: bold;">Eventyr, familieferie eller en romantisk helg?</div>
            <div style="font-size: 60px;">Norge er full av spennenede opplevelser! Planlegg turen, få inspirasjon og supre tips fra loklakjente,.</div>
        </div>
        <div class="po">
Jeg godkjenner alt!
        </div>
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }
    #navbar {
        height: 120px;
        padding-left: 150px;
        padding-right: 150px;
    }
#innhold {
    background-image: url("./bilde1.png");
    margin: auto;
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
    .flagg {
        width: 60px;
    }
    .on {
        margin-top: 450px;
        width: 400px;
        border-radius: 5px;
        background-color: lightgrey;
        opacity: 0.7;
        padding: 20px;
    }
    .po {
        margin-top: 20px;
        width: 800px;
        border-radius: 5px;
        background-color: white;
        padding: 20px;
        height: 300px;
    }
    .tekstMidt {
        margin: auto;
    }
    .test {
        font-size: 120px; 
        font-weight: bold;
    }

</style>
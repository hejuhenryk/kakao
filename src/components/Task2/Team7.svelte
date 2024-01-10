<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>


<section>
 <div class="body">

    <div class="navbar">
        <div class="logo-section">
            <h3>visit 🇳🇴 norway</h3>
        </div>
        <div>
        <small>Offer Favourite Search</small>
        </div>
    </div>

    <!--Hero-->
    <div class="hero-section">
        <div class="hero-card">
            <h1>opplev norge</h1>
            <p>
                <strong>Eventyr, familieferie eller en romantisk helg?<strong>
                Norge er fullt av spennende opplevelser! Planlegg turen, få inspirasjon og supre tips fra lokalkjente.
            </p>
        </div>
    </div>

 </div>
</section>

<style>
.body {
    width: 100%;
    height: 100%;
    background-image: url({bilde1});

}
.navbar {
    display: flex;
    justify-content: space-between;
    max-width: 100%;
    padding: 40px 100px 40px 100px;
    background-color: white;
}
.hero-section {
    height: 90%;
    display: flex;
    align-content: center;
    justify-content: center;
}
.hero-card {
    text-align: center;
    border-radius: 10px;
    background-color: #d3cac3;
}
</style>
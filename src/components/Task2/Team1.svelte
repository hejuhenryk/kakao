<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <nav>
        <div id="visitnorway">
            <h1>Visit</h1>
            <h1>Norway</h1>
        </div>
        <ul id="menuitems">
            <li>Offers</li>
            <li>Favorite</li>
            <li>Search</li>
            <li>Menu</li>
        </ul>
    </nav>
    <div class="big">
        <div id="smol">
            <h2>Opplev Norge</h2>
            <p><b>Eventyr, familieferie eller en romantisk helg?</b></p>
            <p>Norge er fullt av spennende opplevelser! Planlegg turen, få inspirasjon og supre tips fra lokalkjente.</p>
        </div>
        <article id="privacy">
            <div>
                <p>This website uses cookies for personalising ads and for measuring and optimising performance. We share information about your use of our site with our commercial partners. By continuing to use our site, you agree to our privacy and security policy. Please confirm that you consent to our use of cookies.</p>
                <a href="https://vg.no">Personvern- og sikkerhetsvilkår</a>
            </div>
            <div>
                <button id="dark">Ja, det er greit!</button>
                <button id="dark">Kun nødvendige</button>
                <button id="light">Rediger instillinger</button>
            </div>
        </article>
    </div>
</section>

<style>
    /** Input custom css here */
    section {
        color: black;
        background-color: white;
    }

    nav {
        background-color: white;
        color: black;
        padding-top: 4rem;
        padding-bottom: 4rem;
        display: flex;
        flex-flow: nowrap row;
        align-items: center;
        justify-content: space-between;
    }

    #visitnorway{
        display: flex;
        flex-flow: nowrap row;
    }

    #menuitems {
        display: flex;
        flex-flow: nowrap row;
        align-items: center;
        justify-content: right;
        gap: 1rem;
    }

    .big {
        background-image: url("./bilde1.png");
        padding-top: 25rem;
    }

    #smol{
        background-color: grey;
        opacity: 30%;
        border-radius: 2rem;
        display: flex;
        flex-flow: nowrap column;
        align-items: center;
        justify-content: center;
        gap: 2.5rem;
        padding-top: 3rem;
        padding-bottom: 3rem;
        padding-right: 4rem;
        padding-left: 4rem;
    }

    #smol > p {
        font-size: 2rem;
    }

    #privacy {
        display: flex;
        flex-flow: nowrap row;

    }

    #privacy > * {
        display: flex;
        flex-flow: nowrap column;
    }

    button {
        background-color: blue;
        color: white;
    }

</style>

Opplev Norge
Eventyr, familieferie eller en romantisk helg?

Norge er fullt av spennende opplevelser! Planlegg turen, få inspirasjon og supre tips fra lokalkjente.

https://th.bing.com/th/id/R.a24c7430ce582a78db3ca345c6b8114a?rik=fuM7357lyQtUAg&riu=http%3a%2f%2fwww.theflagman.co.uk%2fwp-content%2fuploads%2f2017%2f03%2fflag-of-Norway.jpg&ehk=p1CiZZUAz3jzNW%2fll8ROghxbz%2bqKtnaf2tJV5uwAyBU%3d&risl=&pid=ImgRaw&r=0
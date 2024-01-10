<script lang="ts">
    import bilde1 from "./bilde1.png";
</script>

<section>
<nav>
    <ul>
        <li>THREADS</li>
        <li>INSTAGRAM</li>
        <li>LINKEDIN</li>
    </ul>
    <p><b>ERIK©</b></p>
    <ul>
        <li>WORKS</li>
        <li>ABOUT</li>
        <li>CONTACT</li>
    </ul>
</nav>
<article>
    <h1>CREATIVE DEVELOPER PORTOFOLIO</h1>
    <p>I PASSIONATELY CRAFT CAPTIVATING VISUALS, BLENDING ART AND TECH, FOR DIVERSE CLIENTS, PRIORITIZING ORGINALITY WITH PRECISION AND FLAIR.</p>
    <button>HELLO@ERIKLINSTROM.COM</button>
</article>

<div>
    <p>SELECTED WORK</p>
    <p>{`(2021 - PRESENT)`}</p>
</div>

<img src={bilde1} alt=""/>

</section>

<style>
    section {
        padding-left: 15%;
        padding-right: 15%;
    }

nav {
    display: flex;
    flex-flow: nowrap column;
    align-items: center;
    justify-content: space-between;
    padding-top: 4rem;
    
}

nav > ul {
    display: flex;
    flex-flow: nowrap column;
    gap: 2rem;
}

li {
    font-size: 1.5rem;
    font-weight: 600;
}

article {
    display: flex;
    flex-flow: nowrap row;
    align-items: center;
    justify-content: center;
    gap: 6rem;
}

article > h1 {
    padding-left: 20%;
    padding-right: 20%;
}

article > p {
    padding-left: 30%;
    padding-right: 30%;
}

article > button {
    background-color: white;
    color: black;
    border-radius: 2rem;
}

div {
    display: flex;
    flex-flow: nowrap column;
    justify-content: space-between;
    align-items: center;
}

div > * {
    font-size: 1.5rem;
    font-weight: 500rem;
}

img {
    border-radius: 1rem;
}

</style>
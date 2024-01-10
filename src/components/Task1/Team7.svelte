<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section>
    <!-- change html inside section -->
    <nav>
        <div class="navbar-container">
            <div> <span class="nav-text">Threads</span><span class="nav-text">INSTGRAM</span> <span class="nav-text">Linkedn</span> </div>
            <div>  <span class="title">ERIK©</span> </div>
            <div> <span>works</span><span>about</span><span>contact</span></div>
        </div>
    </nav>
    <div class="hero-container">

    </div>
</section>

<style>
    /** Input custom css here */
    body {
        background-color: #e8e8e8;
    }
    .navbar-container {
        max-width: 800px;
        display: flex;
        justify-content: space-between;
        margin:auto;
        padding: 30px 0 30px 0;
    }
    .navbar-container span {
        text-transform: uppercase;
        margin-right: 20px;
    }
    .title {
        font-size: 20px;
        font-weight: bold;
    }
    .nav-text {
        font-size: 15;
        font-weight: normal;
    }
    .hero-container {
        max-width: 800px;
        margin:auto;
        padding: 120px 0 120px 0;
    }
</style>
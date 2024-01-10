<script lang="ts">
    // import statements here
    import task2 from "./task2.png";
</script>

<header>
    <div class="logo">Visit norway</div>
    <div class="headerbuttons">
        <div class="headerbutton">Offers</div>
        <div class="headerbutton">Favorite</div>
        <div class="headerbutton">Search</div>
        <div class="headerbutton">Menu</div>
    </div>
</header>
<body>
    <div class="middlebox">
        <h1>Opplev Norge</h1>
        <h2>Eventyr, familieferie eller en romantisk helg?</h2>
        <p>Norge er fullt av spennende opplevelser! Planlegg turen, få inspirasjon og supre tips fra lokalkjente.</p>
    </div>
</body>

<style>
    body{
        display: flex;
        justify-content: center;
        background-image: url('task2.png');
        width: 100%;
        
    }
    header{
        display: flex;
        height: 100px;
        justify-content: space-between;
        padding: 20px;
        background-color: white;
        color: black;
        font-size: 13px;
        
    }
    h1{
        font-size: 38px;
    }
    h2{
        font-weight: bold;
        font-size: 18px;
    }
    .headerbuttons{
        display: flex;
    }
    p{
        font-size: 18px;
    }
    .middlebox{
        margin: auto;
        display: flex;
        justify-content: center;
        flex-direction: column;
        text-align: center;
        width: 600px;
        height: 300px;
        font-family: Arial, Helvetica, sans-serif;
        padding: 20px;
        background-color: rgba(255, 255, 255, 0.5);

    }

    .logo{
        font-size: 20px;
        font-weight: bold;
    }
</style>


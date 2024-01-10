<script lang="ts">
    import image1 from "../page1.png"
</script>

<section class="bg-blue-500">
    <header>
        <img src={image1} alt="" />
        <nav>
            <ul>
                <!-- svelte-ignore a11y-invalid-attribute -->
                <li>someLink</li>
            </ul>
        </nav>
    </header>
    <article>
        <h1 class="text-blue-100">Specialists in sustainable digital transformation</h1>
    </article>
    <p>Bjørn Henrik is on the best team (Team 1)!</p>
    <p>Live share test</p>
</section>

<style>
    section {
        color: black;
        background-color: white;
    }

    h1 {
        color: red;
    }
</style>
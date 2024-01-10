<script>
	import { fade, fly } from 'svelte/transition'

    import slide1 from "../slides/slide1.png";
    import slide2 from "../slides/slide2.png";
    import slide3 from "../slides/slide3.png";
    import slide4 from "../slides/slide4.png";
    import slide5 from "../slides/slide5.png";
    import slide6 from "../slides/slide6.png";
	
	const carouselPhotos = [
		slide1,
        slide2,
        slide4,
        slide3,
        slide5,
        slide6
	]
	
	let index = 0
	
	const next = () => {
		index = (index + 1) % carouselPhotos.length
	}
    const preview = () => {
		index = (index - 1) % carouselPhotos.length 
	}
</script>


<section class="grid gap-3 w-3/4 mx-auto my-10">
    <div class="h-[80vh] flex justify-center">
        {#each [carouselPhotos[index]] as src (index)}
            <img in:fly={{ x: '-100%', delay: 100, duration: 300 }} {src} alt=""  class="h-full" />	
        {/each}
    </div>
    <nav  class="flex justify-between mx-20">
        <button disabled={ index === 0} on:click={preview}>Preview</button>
        <div class="flex gap-3">
            {#each carouselPhotos as _, i}
                <button class="{index === i ? "font-bold" : "opacity-90"} px-5 py-2 " on:click={() => index = i}>{i + 1}</button>
            {/each}
        </div>
        <button disabled={ index === (carouselPhotos.length -1)} on:click={next}>Next</button>
    </nav>
</section>

<style>
    button:disabled {
        opacity: 0;
    }   
    img {
        object-fit: contain;
    }
</style>


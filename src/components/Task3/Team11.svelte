<script lang="ts">
    // import statements here
    import bilde1 from "./bilde1.png";
</script>

<section class="class1">
        <div class="waviy">
            <span style="--i:1">G</span>
            <span style="--i:2">R</span>
            <span style="--i:3">U</span>
            <span style="--i:4">P</span>
            <span style="--i:5">P</span>
            <span style="--i:6">E</span>
            <span style="--i:7">_</span>
            <span style="--i:8">1</span>
            <span style="--i:9">1</span>
            <span style="--i:10">_</span>
         
           </div>
    <div style="color:white">
        &#127757;
    </div>
    <div style="display:flex; justify-content:center; align-items:center">
        <span style="font-size:500px; color:white">
            &#9749;
        </span>
    </div>
    <p>KAAAAKKKAAAAAAOOOOO!!!!!!!</p>
</section>

<style>
    /** Input custom css here */


    * {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.class1 {
  background-color:  #151719;
  display: flex;
  justify-content: center;
  align-items: center;
}
.waviy {
  position: relative;
  -webkit-box-reflect: below -20px linear-gradient(transparent, rgba(0,0,0,.2));
  font-size: 60px;
}
.waviy span {
  font-family: 'Alfa Slab One', cursive;
  position: relative;
  display: inline-block;
  color: #fff;
  text-transform: uppercase;
  animation: waviy 1s infinite;
  animation-delay: calc(.1s * var(--i));
  
}
@keyframes waviy {
  0%,40%,100% {
    transform: translateY(0)
  }
  20% {
    transform: translateY(-20px)
  }
}
</style>
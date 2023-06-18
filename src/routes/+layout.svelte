<script>
    import "../../src/style.css"
    import Navbar from "./Navbar.svelte";
    import Icon from "@iconify/svelte"
</script>

<Navbar />

<div class="heroSection container">
        <div class="left">
            <p class="greteing">Hello There <Icon icon="streamline-emojis:hand-with-fingers-splayed-2" width="20px" /></p>
            <h2>Welcome to my Website</h2>
            <p>I am <b style="color:var(--dark_blue)">Suprada Tripathy</b></p>
        </div>
      <div class="right">
        <Icon icon="brandico:github" width="20px" />
           <Icon icon="skill-icons:linkedin" width="20px" />
           <Icon icon="logos:google-gmail" width="20px" />
     </div>
</div>

    <slot />
<footer class="container">
  <i>made using love and svelte.js</i>
</footer>

<style>
  .heroSection{
    padding: 20px 0px;
    text-align: center;
  }
  .greteing{
    font-size: 1vw;
  }
  p{
    margin:0px;
    font-weight: 300;
  }

  h2{
    margin: 0px;
    font-weight: 900;
    font-size: 5vw;
  }
 footer{
  padding: 20px 0px;
  text-align: center;
 }
 .right{
  display: flex;
  gap:20px;
  justify-content: center;
  align-items: center;
  padding: 20px 0px;
 }
</style>


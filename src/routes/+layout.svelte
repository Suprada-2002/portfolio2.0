<script>
    import "../../src/style.css"
    import Navbar from "./Navbar.svelte";
</script>

<Navbar />
<slot />
<footer class="container">
  <i>made using love and svelte.js</i>
</footer>

<style>
 footer{
  padding: 20px 0px;
  text-align: center;
 }
</style>


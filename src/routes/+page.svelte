<script>
  import Icon from '@iconify/svelte';
  import HeroSection from './HeroSection.svelte';

  let project = [
    {
      title: "Blog App",
      desc: "place where i write my thoughts",
      href: "/"
    },
    {
      title: "Sign Book",
      desc: "If u are here please got my sign book and sign it",
      href: "/"
    }
  ]
</script>

<HeroSection />
<div class="container">
  <div class="project">
    <ul>
    {#each project as {desc,href}}
    <li><a {href}>{desc}</a></li>
    {/each}
  </ul>
  </div>
</div>

<style>
  ul{
    display: grid;
    grid-template-columns: 1fr 1fr;
    place-items: center;
    list-style: none;
  }
  li{
    border: 1px solid white;
  }
   a{
    text-decoration: none;
    color: var(--white);
   }
</style>
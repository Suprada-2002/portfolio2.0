<script>
  import Icon from '@iconify/svelte';
</script>

<div class="container">
    <div class="blog">
      <div class="heroIcon">
        <Icon icon="openmoji:writing-hand-light-skin-tone" width="40" />
      </div> 
      <div class="content">
        <a href="/">A place where i write about my thoughts</a>
      </div>
    </div>
</div>

<style>
  .content{
    font-weight: 300;
    display: grid;
    place-items: center;
  }
  .blog{
    color:var(--white);
    width: 80%;
    border: 1px solid var(--white);
    display: flex;
  }
  .heroIcon {
    writing-mode: vertical-lr;
    padding: 5px 5px;
  }
   a{
    text-decoration: none;
    color: var(--white);
   }
</style>
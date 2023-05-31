<script>
  import {page} from '$app/stores';
  import Icon from '@iconify/svelte';

    const navs = [
        {
            title:"Home",
            href:"/"
        },
        {
            title:"About",
            href:"/about"
        },
        {
            title:"Projects",
            href:"/projects"
        },
        {
            title:"Contact",
            href:"/contact"
        }
    ]

  $: routeId = $page.route.id;
</script>

<nav>
    <div class="container">
        <Icon icon="svg-spinners:blocks-shuffle-3" width="40"  />
        <ul>
            {#each navs as {title, href}}
           <li><a {href} class:active={
            routeId === href
           }>{title}</a></li>
           {/each}
        </ul>
    </div>
    </nav>

    
       <style> 
    nav{
        color: var(--pink);
        padding: 0.5em;
    }
    
      .container{
        display:flex;
        align-items: center;
     }
       ul{
           display:flex;
           margin: 0px;
           margin-left: auto;
           list-style: none;
       }
       
       li{
           margin-right: 10px;
       }
    h3{
        margin: 0px;
        font-size: 1.3rem;
    }
    
    a{
        text-decoration: none;
        color: rgb(112, 101, 101);
    }

    .active{
        color:var(--pink);
    }
       </style>
    
    
    
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

<nav class="container">
        <ul>
            {#each navs as {title, href}}
           <li><a {href} class:active={
            routeId === href
           }>{title} </a> | </li>
           {/each}
        </ul>
    </nav>

    
       <style> 
    nav{
       padding: 20px 0px;
        
    }
    ul{
        display: flex;
        justify-content: center;
        align-items: center;
        list-style: none;
    }
   
       li{
           margin-right: 10px;
       }
       a{
        text-decoration: none;
        color: var(--white)
    }
    .active{
        color:var(--light_blue);
    }

       </style>
    
    
    
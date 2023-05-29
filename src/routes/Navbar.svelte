<script>
  import {page} from '$app/stores';

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
        <h3>Suprada Tripathy</h3>
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
        background-color: rgb(32, 32, 30);
        color: white;
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
        color: rgb(190, 189, 189);
    }

    .active{
        color:white;
    }
       </style>
    
    
    
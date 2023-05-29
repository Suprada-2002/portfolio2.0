<script>
  import {page} from '$app/stores';
  $: routeId = $page.route.id;
</script>

<nav>
    <div class="container">
        <h3>Suprada Tripathy</h3>
        <ul>
           <li><a href="/" class:active={
            routeId === '/'
           }>Home</a></li>
           <li><a href="/about" class:active={
            routeId === '/about'
           }>About</a></li>
           <li><a href="/projects" class:active={
            routeId === '/projects'
           }>Projects</a></li>
           <li><a href="/contact" class:active={
            routeId === '/contact'
           }>Contact</a></li>
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
    
    
    
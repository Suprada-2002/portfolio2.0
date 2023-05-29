<nav>
<div class="container">
    <h3>Suprada Tripathy</h3>
    <ul>
       <li><a href="/">Home</a></li>
       <li><a href="/about">About</a></li>
       <li><a href="/projects">Projects</a></li>
       <li><a href="/contact">Contact</a></li>
    </ul>
</div>
</nav>
   
   <slot />

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
    color: white;
}
   </style>



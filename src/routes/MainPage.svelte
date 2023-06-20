<script>
    import Icon from '@iconify/svelte';
  
    let interest = [
      {
        title: "Anime",
        href: "/anime"
      },{
        title: "Music",
        href: "/music"
      },{
        title:"Kdrama",
        href:"/drama"
      }
    ]
  
    let network = [
      {
        title:"My Git",
        href:"https://github.com/Suprada-2002"
      },{
        title: "Instagram",
        href:"https://www.instagram.com/suprada__tripathy/"
      },{
        title:"LinkedIn",
        href:"https://www.linkedin.com/in/suprada-tripathy-2981a1201/"
      }
    ]
  </script>

<div class="container">
    <div class="left">
      <div class="network">
        <h3>Network</h3>
        {#each network as {title, href}}
          <ul>
            <li><a {href}>{title}</a></li>
          </ul>
        {/each}
      </div>
      <div class="interest">
        <h3>Interest</h3>
        {#each interest as {title, href}}
          <ul>
            <li><a {href}>{title}</a></li>
          </ul>
        {/each}
      </div>
    </div>
  <div class="right">
     right
  </div>
  </div>
  
  <style>
  .container {
    display: grid;
    grid-template-columns: 1fr 4fr;
    gap:20px
  }
    ul{
     padding: 0px;
      list-style: none;
      margin: 0.5px;
      display: grid;
      place-items: center;
      cursor: pointer;
    }
    li{
      font-weight: 300;
    }
    a:hover{
        color: var(--dark_blue);
    }
    h3{
        margin: 0px;
    }
     a{
      text-decoration: none;
      color: var(--white);
      border-bottom: 1px dotted var(--light_blue);
     }
     .network, .interest{
        padding-bottom: 20px;
        text-align: center;
     }
  </style>
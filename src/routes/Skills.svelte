<script>
    import Icon from "@iconify/svelte";

    let tools=[
        {
            title:"vs code",
            icon:""
        },{
            title:"Vim",
            icon:""
        },{
            title:"Nano",
            icon:""
        }
    ]

    let framework = [
        {
            title:"React.js",
            icon:"skill-icons:react-dark"
        },{
            title:"Next.js",
            icon:""
        },{
            title:"Svelte.js",
            icon:"skill-icons:svelte"
        },{
            title:"Vue.js",
            icon:"skill-icons:vuejs-dark"
        },{
            title:"style-components",
            icon:"skill-icons:styledcomponents"
        }
    ]

    let language = [
        {
            title:"Javascript",
            icon:"skill-icons:javascript"
        },{
            title:"Python",
            icon:"skill-icons:python-dark"
        },{
            title:"C",
            icon:"skill-icons:c"
        },{
            title:"C++",
            icon:"skill-icons:c"
        },{
            title:"Node.js",
            icon:"skill-icons:nodejs-dark",
        },{
            title:"Java",
            icon:"skill-icons:java-dark"
        }
    ]
</script>

<div class="container">
    
    <div class="language">
        <ul>
            {#each language as {title,icon}}
            <li><i>{title}</i><span><Icon icon={icon} width="20px"/></span></li>
            {/each}
        </ul>
    </div>
    <div class="tools">
        <ul>
            {#each tools as {title,icon}}
            <li><i>{title}</i><span><Icon icon={icon} width="20px"/></span></li>
            {/each}
        </ul>
    </div>
    <div class="framework">
        <ul>
            {#each framework as {title,icon}}
            <li><i>{title}</i><span><Icon icon={icon} width="20px"/></span></li>
            {/each}
        </ul>
    </div>
</div>

<style>
ul{
   list-style: none;
   display: flex;
   gap: 15px;   
}
li{
    display: flex;
    gap:10px;
    padding: 3px 5px;
    background-color: var(--light_blue);
    color: var(--dark_black);
    font-weight: 800;
    border-radius: 4px;
}
</style>
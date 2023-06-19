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
            icon:""
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
    <div class="skill-section languages">
        <h4>Languages</h4>
        <div class="skill-icon">
        <Icon icon="skill-icons:javascript" width="30px" />
        <Icon icon="skill-icons:python-dark" width="30px" />
        <Icon icon="skill-icons:c" width="30px" />
        <Icon icon="skill-icons:java-dark" width="30px" />
        <Icon icon="skill-icons:nodejs-dark" width="30px" />
        </div>
     </div>

     <div class="skill-section farmework">
        <h4>Framework</h4>
        <div class="skill-icon">
            <Icon icon="skill-icons:svelte" width="30px" />
            <Icon icon="skill-icons:react-dark" width="30px" />
            <Icon icon="skill-icons:nextjs-dark" width="30px" />
            <Icon icon="skill-icons:vuejs-dark" width="30px" />
            <Icon icon="skill-icons:tailwindcss-dark" width="30px" />
            <Icon icon="skill-icons:styledcomponents" width="30px" />
        </div>
     </div>

     <div class="skill-section db">
        <h4>Database</h4>
        <div class="skill-icon">
            <Icon icon="skill-icons:mongodb" width="30px" />
            <Icon icon="skill-icons:mysql-dark" width="30px" />
            <Icon icon="vscode-icons:file-type-firebase" width="30px" />
            <Icon icon="skill-icons:supabase-dark" width="30px" />
        </div>
     </div>

     <div class="skill-section tech">
        <h4>Tech</h4>
        <div class="skill-icon">
            <Icon icon="skill-icons:postman" width="30px" />
            <Icon icon="skill-icons:figma-dark" width="30px" />
            <Icon icon="devicon:css3" width="30px" />
            <Icon icon="skill-icons:html" width="30px" />
        </div>
     </div>
  

</div>

<style>
    .container{
        display: grid;
        grid-template-columns: 1fr 1fr;
        place-items: center;
    }
    .skill-section{
      display: flex;
        padding-top: 50px;
        align-items: center;
    }
    h4{
        writing-mode: vertical-lr;
    }

    .skill-icon{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        gap:10px;
    }
</style>
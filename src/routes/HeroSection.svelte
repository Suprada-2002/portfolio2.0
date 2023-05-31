<script>
    import Icon from "@iconify/svelte";
</script>

<div class="hero">
    <div class="container"> 
     <h6>Hello there,I am</h6>
     <h3>Suprada Tripathy</h3>
     <h6>Welcome to my Website</h6>
     <div class="hh">
        <Icon icon="skill-icons:styledcomponents" />
           <Icon icon="skill-icons:react-dark" />
           <Icon icon="skill-icons:postman" />
     </div>
    </div>
</div>

<style>
    h6,h3{
        margin: 0;
        color: var(--white);
    }
    .container{
        padding: 3rem 0px;
        color: var(--dark-text);
    }
    h6{
        font-weight: 300;
        font-size: 1.6vw;
    }

    h3{
        font-weight: 700;
        font-size: 4vw;
    }

    .hh{
        float: right;
        display: flex;
        flex-direction: column;
    }
</style>
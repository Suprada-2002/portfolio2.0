<script>
    import Icon from "@iconify/svelte";
</script>

<div class="hero">
    <div class="container"> 
        <div class="left">
            <h6>Hello there,I am</h6>
            <h3>Suprada Tripathy</h3>
            <h6>Welcome to my Website</h6>
        </div>
      <div class="right">
        <Icon icon="brandico:github" width="30px" />
           <Icon icon="skill-icons:linkedin" width="30px" />
           <Icon icon="logos:google-gmail" width="30px" />
     </div>
    </div>
</div>

<style>
    h6,h3{
        margin: 0;
        color: var(--white);
    }
    .container{
        display: flex;
        flex-direction: row;
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

    .left{
        flex: 90%;
    }
    .right{
        flex: 10%;
        gap:20px;
       display: flex;
       flex-direction: column;

    }
</style>
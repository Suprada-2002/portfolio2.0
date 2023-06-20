<script>
    let songs = [
        "AC/DC - Back in Black","RedBone - Come and Get Your Love",
        "Bruno Mars - Finesse", "Taylor Swift - Wildest Dreams",
        "Fifty Fifty - Cupid"
    ]

</script>

<div class="container">
    <div class="songs">
        <ul>
        {#each songs as name,index}
        <li>{index+1} . {name}</li>
        {/each}
    </ul>
    </div>
</div>

<style>
    ul{
        list-style: none;
    }
</style>
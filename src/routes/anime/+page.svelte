<script>
    let photos = [
        {
            name:"Jujitsu Kaisen",
            path:"../../../static/jjk.jpeg"
        },{
            name:"Naruto",
            path:"../../../static/naruto.jpg"
        },
        {
            name:"Bleach",
            path:"../../../static/bleach.jpg"
        },{
            name: "Bungo Stray Dogs",
            path:"../../../static/bungoStrayDogs.jpeg"
        }
    ]

    let japneseAnime = [
        "Loving Yamada at lvl 999", "Insomniacs After School", "Mashle: Magic and Muscles","Hell's Paradise: Jigokuraku", "Demon Slayer", 
        "Naruto","Bleach", "Chainsaw Man", "Death Note","Jujutsu Kaisen", "Spy x Family", "Haikyu", "Tokyo Revengers", "Fire Force", "Horimiya"
    ]

    let chineseAnime = ["The Island of Siliang","Mo Dao Zu Shi", "Heaven Official's Blessing"]
</script>

<div class="container">

    <div class="memes">
        {#each photos as {name,path}}
        <div class="memePhoto">
            <img src={path} alt="uu" />
            <p>{name}</p>
        </div>
        {/each}
    </div>
    <div class="names">
        <i>Learn to treasure your life beacuse unfortunately, it can be taken away from you anytime. - L Lawliet(Death Note)</i>
        <p>Favorites so far..</p>
       <ul>
            {#each japneseAnime as name, index}
            <li>{index+1} . {name}</li>
            {/each}
       </ul>
       <p>Chinese dramas.. </p>
       <ul>
        {#each chineseAnime as name, index}
        <li>{index+1} . {name}</li>
        {/each}
   </ul>
    </div>
</div>

<style>
    .container{
        display: grid;
        grid-template-columns: 1fr 3fr;
    }
    .memes{
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
    }
    img {
        display: block;
        height: auto;
        max-width: 100%;
    }
    .memePhoto{
        width:250px;
        display: grid;
        place-items: center;
    }
    ul{
        list-style: none;
    }
</style>
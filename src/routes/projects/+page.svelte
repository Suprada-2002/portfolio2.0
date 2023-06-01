
<div class="projects">
    <div class="container">
        <div class="one left">
            <h2>Know Your Course</h2>
            <h3>Tech Used:React.js, firebase, styled-components</h3>
            <p>This is app where people can post about there exprencince on taking a course. Beginners can Used
                this to know which course they sould take to learn the new experience.
            </p>
            <img src="../../static/favicon.png" alt="photo" />
        </div>
        <div class="two right">
            <h2>Visualizer of A* Algorithm</h2>
            <h3>Tech Used:React.js, firebase, styled-components</h3>
            <p>This is app where people can post about there exprencince on taking a course. Beginners can Used
                this to know which course they sould take to learn the new experience.
            </p>
            <img src="../../static/favicon.png" alt="photo" />
        </div>
        <div class="three left">
            <h2>Blog App</h2>
            <h3>Tech Used:React.js, firebase, styled-components</h3>
            <p>This is app where people can post about there exprencince on taking a course. Beginners can Used
                this to know which course they sould take to learn the new experience.
            </p>
            <img src="../../static/favicon.png" alt="photo" />
        </div>
        <div class="four right">
            <h2>Command Line Quiz app</h2>
            <h3>Tech Used:React.js, firebase, styled-components</h3>
            <p>This is app where people can post about there exprencince on taking a course. Beginners can Used
                this to know which course they sould take to learn the new experience.
            </p>
            <img src="../../static/favicon.png" alt="photo" />
        </div>
    </div>
</div>

<style>
    .container {
        display: grid;
        grid-template-columns: 1fr;
    }

    .left > *{
        float:left;
    }
    .right > *{
        float:right;
    }

    .one {
        display: flex;
        flex-direction: column;
    }

    img {
        max-width: 100px;
    }

    @media screen and (max-width: 800px){
        h2,h3{
            float:none;
        }
    }
</style>
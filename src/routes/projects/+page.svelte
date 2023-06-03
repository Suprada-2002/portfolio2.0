
<div class="projects-section">
    <div class="container">

        <div class="row">
            <div class="col66">
                <h2>Know Your Course</h2>
                <p><b>Tech Used :</b>React.js, firebase, styled-components</p>
                <p>This is app where people can post about there exprencince on taking a course. Beginners can Used
                    this to know which course they sould take to learn the new experience.
                </p>
                <button>live</button>
            </div>
            <div class="col33">
                <img src="../../static/favicon.png" alt="photo" />
            </div>
      </div>


        <div class="row">
            <div class="col33">
                <img src="../../static/favicon.png" alt="photo" />
            </div>
            <div class="col66">
                <h2>Know Your Course</h2>
                <p><b>Tech Used :</b>React.js, firebase, styled-components</p>
                <p>This is app where people can post about there exprencince on taking a course. Beginners can Used
                    this to know which course they sould take to learn the new experience.
                </p>
                <button>live</button>
            </div>
        </div>

    </div>
</div>

<style>
.row{
    padding: 20px 0px;
    display: flex;
    align-items: center;
}

.row:after {
    content: "";
    display: table;
    clear: both;
}

.col66 {
    float: left;
    width: 66%;
    padding: 10px;
}

.col33 {
    float: left;
    width: 33%;
    padding: 10px;
}
   
    img {
        display: block;
        padding-left: 20px;
        height: auto;
        max-width: 100%;
    }

    @media screen and (max-width: 1000px){
        .col66, .col33{
            width: 100%;
            text-align: center;
        }
        img {
            margin: auto;
        }
        .row {
            display: block;
        }
    }
</style>
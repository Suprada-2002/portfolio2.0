<script>
  import Skills from "../Skills.svelte";

</script>
<div class="about">
    <div class="container">
         <div class="about-hero">
            <h4>About me</h4>
            <p>My name is Suprada Tripathy.I am computer science graduate from India. Self taught web deveoper and linux enthusiast.
                With every line of code i strive to make the web the a better palce. 
            </p>
         </div>
         <div class="internship">
            <h4>Internship</h4>
            <div class="intern-content">
            <h3>Highradius Corporation <span><i>06/2022-04/2023</i></span></h3>
            <p>Associate Software Intern</p> 
        </div>
         </div>
         <div class="studies">
            <h4>Education</h4>
            <div class="graduation">
               <h3>Bachleour in Technology <span><i>2019-2023</i></span></h3>
               <p>Gandhi Institute of Engineering and Technology</p> 
                <p>Computer Science and Engineering</p> 
                <h3>Intermediate <span><i>2017-2019</i></span></h3>
                <p>Kalahandi University</p> 
                <p>PCMB</p> 
                <h3>Matriculation <span><i>2017</i></span></h3>
                <p>Sri Sathya Sai Vidhya Mandir</p> 
                <p>Science</p> 
            </div>
         </div>
    </div>
</div>
<Skills />

<style>
    span{
        font-size: 10px;
        padding-left: 30px;
    }
    .container{
        padding-top: 30px;
    }
    .studies, .internship{
        display: flex;
        padding-top: 50px;
        align-items: center;

    }
    .about-hero {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    p{
        margin: 0px;
        color: var(--white);
        font-weight: 300;
    }
    h4{
        writing-mode: vertical-lr;
    }
    
</style>
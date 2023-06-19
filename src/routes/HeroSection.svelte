<script>
    import Icon from '@iconify/svelte';
  </script>

<div class="heroSection container">
    <div class="left">
        <p class="greeting">Hello There <Icon icon="streamline-emojis:hand-with-fingers-splayed-2" width="20px" />, I am</p>
        <h2><i>Suprada Tripathy</i></h2>
        <p><b style="color:var(--dark_blue)">Welcome to my Website</b></p>
    </div>
  <div class="right">
    <Icon icon="brandico:github" width="20px" />
       <Icon icon="skill-icons:linkedin" width="20px" />
       <Icon icon="logos:google-gmail" width="20px" />
 </div>
</div>

<style>
     .heroSection{
    padding: 20px 0px;
    text-align: center;
  }
  .greeting{
    font-size: 1.3vw;
  }
  p{
    margin:0px;
    font-weight: 300;
  }
  .right{
  display: flex;
  gap:20px;
  justify-content: center;
  align-items: center;
  padding: 20px 0px;
 }
 h2{
    margin: 0px;
    font-weight: 900;
    font-size: 5vw;
  }
</style>
<script>
  import extr from "C:/Users/aksha/Documents/IEEE_Website/src/album.png"
</script>

<main>
  <span class="container">
    <span class="topic">
      <a href="https://extract.pics/" target="_self" rel="noreferrer"> 
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src={extr} alt="Image-Extractor" class="fimg">
        <span class="imgnm">Image Extractor</span>
      </a>
      <a href="https://extract.pics/changelog" target="_self" rel="noreferrer"> 
        <span class="imgver">VERSION 2.4.0</span>
      </a>
    </span>

    <span class="mname">
      EXTRACT IMAGES
    </span>

    <span class="desci">
      From any public website by using a virtual browser
    </span>

    <div class= "box-white">
      <span class="ent">
        Enter URL...
      </span>
    </div>

    <div class= "box-green">
      <span class="sub">
        EXTRACT
      </span>
    </div>

    <div class="sett">
      settings
    </div>

    <div class="clr">
      Clear URL and images
    </div>

    <span class="headings">
      <a href="https://extract.pics/api" target="_self" rel="noreferrer"> 
        <span class="api">API</span>
      </a>
      <a href="https://www.buymeacoffee.com/pabue" target="_self" rel="noreferrer"> 
        <span class="dnt">Donate</span>
      </a>
      <a href="https://extract.pics/feedback" target="_self" rel="noreferrer"> 
        <span class="fb">Feedback</span>
      </a>
      <a href="https://extract.pics/about" target="_self" rel="noreferrer"> 
        <span class="abt">About</span>
      </a>
    </span>
  </span>
  <span class= "ac-text">

  </span>
</main>

<style>
  .sett{
    font-family: 'calibri' "bold";
    font-size: 20px;
    position: relative;
    top: 21px;
    left: -260px;
    color: rgb(225, 210, 210);
  }
  .clr{
    font-family: 'calibri' "bold";
    font-size: 18px;
    position: relative;
    top: -1px;
    left: -110px;
    color: rgb(225, 210, 210);
  }
  .sub{
    font-family: 'holdy trial' "bold"; 
    letter-spacing: 2px;
    position: relative;
    left: -6px;
  }
  .ent{
    font-family: 'calibri' "bold"; 
    font-size: 1.1em;
    position: relative;
    left: -210px;
    color: black;
  }
  .box-green{
    border-radius: 10px;
    position: absolute;
    top: 300px;
    left: 1040px;
    height: 25px;
    width: 70px;
    border: 20px solid #318e32;
    background-color: #318e32;
  }
  .box-white{
  border-radius: 10px;
  position: absolute;
  top: 300px;
  left: 440px;
  width: 550px;
  border: 20px solid white;
  background-color: white;
  }
  .desci{
    font-family: 'calibri' "bold"; 
    font-size:1.5em;
    font-weight: 500;
    position: absolute;
    top: 250px;
    left: 490px;
    word-spacing: -3px;
    letter-spacing: 2px;
  }
  .mname{
    font-family: 'calibri' "bold"; 
    font-size:3em;
    font-weight: 700;
    position: absolute;
    top: 200px;
    left: 540px;
    word-spacing: -2px;
    letter-spacing: 5px;
  }
  .container{
    background-color: white !important;
  }
  .headings{
    letter-spacing: 5px;
    word-spacing: 5px;
    position: fixed;
    top:40px;
    left:1150px;
  }
  .topic{
    position: fixed;
    top:40px;
    right:1250px;
  }
  .fimg{
    height: 25px;
    padding: 1px;
  }
  .fimg:hover{
    filter: drop-shadow(0 0 2em #15ff19aa);
  }
  .imgnm{
    font-family: 'calibri';
    font-size:1.1em;
    position:relative;
    left:8px;
    top:-8px;
    color: white;
  }
  .imgnm:hover{
    filter: drop-shadow(0 0 1em grey);
  }
  .imgver{
    font-family: 'calibri';
    font-size: 0.9em;
    position:relative;
    right:108px;
    top:13px;
    color: #34D399;
  }
  .api{
    color:rgb(226, 225, 225);
  }
  .dnt{
    color:rgb(226, 225, 225);
  }
  .fb{
    color:rgb(226, 225, 225);
  }
  .abt{
    color:rgb(226, 225, 225);
  }
  .api:hover{
    text-decoration: underline;
    color:rgb(226, 225, 225);
  }
  .dnt:hover{
    text-decoration: underline;
    color:rgb(226, 225, 225);
  }
  .fb:hover{
    text-decoration: underline;
    color:rgb(226, 225, 225);
  }
  .abt:hover{
    text-decoration: underline;
    color:rgb(226, 225, 225);
  }
</style>
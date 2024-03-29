# ac173.portfolio.io
<!DOCTYPE html>
<html>
  <!--<head>
    <title>Kate Curry Portfolio</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
    .w3-row-padding img {margin-bottom: 12px}
    /* Set the width of the sidebar to 120px */
    .w3-sidebar {width: 120px;background: #222;}
    /* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
    #main {margin-left: 120px}
    /* Remove margins from "page content" on small screens */
    @media only screen and (max-width: 600px) {#main {margin-left: 0}}
    </style>
  </head>
<body class="w3-black">
<!-- change "w3-grey" from "w3-black"-->
-->
<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-grey">
  <!-- changed w3-grey from w3-black-->
    <i class="fa fa-home w3-xxlarge"></i>
    <p>PROJECTS</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT ME</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <!-- ><a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a> -->
    <!-- ><a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a> -->
    <!-- COMMENTING OUT UNECESSARY CODE IN CASE I WANT TO COME BACK TO USE IT LATER-->
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-grey" id="home">
  <!-- change w3-white from w3-black-->
    <h1 class="w3-jumbo"><span class="w3-hide-small"></span> My Portfolio</h1>
    <p>Below are my School Projects.</p>
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">Kate Curry</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>I am a current student at the University of South Carolina Beaufort. I am studying Information Technology and Science with a concentration in
      cybersecurity and a minor in Spanish.
    </p>
    <h3 class="w3-padding-20 w3-text-light-grey">My Projects</h3>
    <p class="w3-padding-20 w3-text-light-grey">Python Reseach Project:</p>
    <p class="w3-padding-20 w3-text-light-grey">My partner and I were tasked with extracting data
    into an Excel sheet from a CDC survey dataset, and finding a correlation between two of the survey
    questions. To find the correlation, we imported all of the data into Python and used bar graphs, heat maps,
    and pie charts to see which answers had correlation from the survey.</p>
    <p class="w3-padding-20 w3-text-light-grey">Our code:</p>
    <a href="B104_ProjectScript_Group01.py.zip">B104_ProjectScriptGroup.py.zip</a>
    <p class ="w3-padding-20 w3-text-light-grey"> Object-Oriented Programming I Project:</p>
    <p class="w3-padding-20 w3-text-light-grey">I was tasked with creating a video game, using the Greenfoot application,
    and basing the game off of my assigned art movement- Dadaism. We were required to incorporate tangential learning into
    our games so that our games were not strictly educational, but instead helped to spark interest in learning more about
    what our games were inspired by.</p>
    <p class="w3-padding-20 w3-text-light-grey">I received an Honorable Mention from my instructor, Dr. Brian Canada, my peers and fellow
    classmates, and alumni from the Object-Oriented Programming I class, which landed me a "Silver Medal" out of all of the games 
    that my class had created.</p>
    <p class="w3-padding-20 w3-text-light-grey">The link to my game- Everyday Art:</p>
    <a href="https://www.greenfoot.org/scenarios/32487?js=true">Everyday Art- Object-Oriented Programming Project</a>
    <div class="w3-white">
   
    </div>
  
  
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Posters</h2>
    <img src ="">
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="B104_ResearchPoster.png" style="width:100%">
        <p class="w3-padding-20 w3-text-light-grey">Our Research Poster for the Python project</p>
      </div>

      <div class="w3-half">
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Bluffton, SC</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: 843.941.9888</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: ac173@email.uscb.edu</p>
    </div><br>
    <p>Let's get in touch. Send me a message:</p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
<!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
<footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
 <p class="w3-small">This website was made with W3schools Spaces. Make your own free website today!</p>
 <a class="w3-button w3-round-xxlarge w3-small w3-light-grey" href="https://www.w3schools.com/spaces" target="_blank">Start now</a> 
 <!-- End footer -->
</footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>

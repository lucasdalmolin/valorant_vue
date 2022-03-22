

<template>




<img id="fondo" src="./assets/images/VALORANT_logo4.jpg" alt="">

            <!-- NAVBAR -->

<div id="navbar" class="row">
  <div id="border-right" class="col l2 blue">3</div><!-- BORDE DER -->


<!-- NAVBAR  COMPONENT -->
  <div id="navbar-nav" class="col l8 m9 s12 red">
    <nav>
    <div class="nav-wrapper">
        <a href="#" class="col s3 brand-logo">
        <img class="responsive-img" src="./assets/images/VALORANTGG_logo.png" alt="">
      </a>
      

      
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">Sass</a></li>
        <li><a href="badges.html">Components</a></li>
        <li><a href="collapsible.html">JavaScript</a></li>
      </ul>

    </div>
  </nav>



  </div>

  <div id="border-left" class="col l2 m0blue">3</div> <!-- BORDE IZQ -->
</div>

            <!--  MAIN   -->
<div id="main" class="row">
  <div id="border-right" class="col l2 center blue">3</div>
  <div id="main" class="col l8 s12 center red">
    <div id="section-1"></div>

    <div id="section-2"></div>
  </div>
  <div id="border-left" class="col l2 center blue">3</div>
</div>







</template>


<style>
  :root {
    --clr-1: #ff4655;
  }

  *, *::after, *::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  #fondo {
    position: fixed;
    width: 100vw;
    height: 100vh;
    opacity: 0.9;
    z-index: -10;
  }

  /** NAVBAR  **/

  #navbar {
    position: fixed;
    width: 100vw;
  }

  #section-1 { /** IMAGEN DE KILLJOY  **/
    background-image: url("./assets/images/KillJoy_Wallpapers_blue1.jpg");
    background-repeat: no-repeat;
    height: 100vh;
    background-size: cover;
  }

  #section-2 { /** IMAGEN DE KILLJOY  **/
    background-image: url("./assets/images/KillJoy_Wallpapers_blue1.jpg");
    background-repeat: no-repeat;
    height: 100vh;
    background-size: cover;
  }
</style>



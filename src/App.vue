

<template>




<img id="fondo" src="./assets/images/VALORANT_logo4.jpg" alt="">

            <!-- NAVBAR -->

<div id="navbar" class="row">
  <div id="border-right" class="col l2 s0"></div><!-- BORDE DER -->


<!-- NAVBAR  COMPONENT -->
  <div id="navbar-nav" class="col l8 m12 s12">
    <nav>
    <div class="nav-wrapper">

      <!-- LOGOTIPO -->
      <a href="#" class="col s2 brand-logo ">
        <img class="responsive-img" src="./assets/images/VALORANTGG_logo.png" alt="">
      </a>

      <!-- LUPA -->
      <!-- <label class="label-icon col s1 right" for="search">
          <i class="material-icons">search</i>
      </label> -->

      

      <!-- SEACHING INPUT -->
      <ul class="col s3 right">
        <form>
          <div class="buscador">
            <input id="search" type="search" placeholder="Buscar..." required>
          </div>
        </form>
      </ul>
    </div>
  </nav>



  </div>


  <div id="border-left" class="col l2 s0"></div> <!-- BORDE IZQ -->
</div>


            <!-- SIDE NAVBAR -->
<div class="row">
  <div class="col l2"></div><!-- BORDE DER -->

  <div class="col l8 s12 red row">

    <div id="side-navbar" class="col s2">

      <ul class="center side-navbar">

        <li><a href="#">HOME</a></li>
        <li><a href="#">AGENTES</a></li>
        <li><a href="#">RANKING & STATS</a></li>
        <li><a href="#">REPLAYS</a></li>
        <li><a href="#">CONFIG</a></li>

      </ul>

    </div>

    
  </div>

  <div class="col l2"></div><!-- BORDE IZQ -->
</div>


            <!--  MAIN   -->
<div id="main" class="row">
  <div id="border-right" class="col l2 center"></div><!-- BORDE DER -->


  <div id="sections" class="col l8 s12 center z-depth-5">



    <div id="section-1"></div>



    <div id="section-2"></div>
  </div>


  <div id="border-left" class="col l2 center"></div><!-- BORDE IZQ -->
</div>







</template>


<style>
  :root {
    --clr-1: #ff4655;
    --clr-2: #111;

    --clr-txt: white;

    --nav-h: 60px;
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

  .col, .row {
    margin: 0 !important;
    padding: 0 !important;
  }
  /** NAVBAR  **/

  #navbar {
    position: fixed;
    width: 100vw;
    z-index: 10;
  }
  .nav-wrapper, nav {
    padding: 0rem 0rem 0.5rem 1rem;
    height: var(--nav-h);
    background-color: var(--clr-2);
  }


  #search {
    background-color: var(--clr-1);
    color: var(--clr-txt);

    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS',sans-serif ;
    font-size: 1.3rem;

    height: 2rem;
    width: 14rem;
    padding-left: 20px;

    clip-path: polygon(0% 0%, 80% -10%, 100% 100%, 80% 100.00%, 0% 100%, 0px -10px);
    
  }

  /** MAIN SECTION  **/
  #main {
    transform: translateY(var(--nav-h));
  }
  #sections {
    background-color: var(--clr-txt);
  }

  /** SIDE NAVBAR  **/

  #side-navbar {
    position: fixed;
    transform: translateY(var(--nav-h));
    background-color: #111;
    height: 100vh;
    z-index: 9;
  }
  .side-navbar > * {
    padding: 20px;
    border: rgb(255, 255, 255) 1px solid;
  }
  .side-navbar > :last-child { /** xD */
    align-items: flex-end;
  }
  a {
    color: var(--clr-txt);
  }


  #section-1 { /** IMAGEN DE KILLJOY  **/
    background-color: #ff4655;
    height: 100vh;
    clip-path: polygon(80% 0%, 100% 0%, 100.00% 66.33%, 60% 100%, 0% 100%, 0px 0px);
  }


  #section-2 { /** IMAGEN DE KILLJOY  **/
    background-color: var(--clr-txt);
    height: 100vh;
    /* clip-path: polygon(80% 0%, 100% 20%, 100% 100%, 80% 100%, 0% 100%, 0px 0px); */
    z-index: -10 !important;
  }
</style>



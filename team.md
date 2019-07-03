---
layout: page
title: Pomès Lab - Team
description: When building a website it's helpful to see what the focus of your site is. This page is an example of how to show a website's focus.
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---
<style type="text/css">

.header-text {
  text-align: center;
  margin: 2% 0% 0% 0%;
}

.title {
  font-weight: bold;
  text-align: center;
}

.centerwrapper
{
   margin: auto;
   width: 100%;
   text-align: center;
}

.centered-and-cropped {
  object-fit: cover;
  overflow: hidden;
  width: 180px;
  height: 180px;
  background-color: white;
  border-radius:50% ;
  border: 3px solid grey;
  max-width:100%;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.column {
  margin: auto;
  padding: 0 1.5%;
  max-width: 100%;
  text-align:left;
  display:inline-block;
}


.card {
  transition: 0.3s;
  border-radius: 5px;
  <!--background-color: #f1f1f1;-->
}

.card-deck {
  text-align: center;
}

.container {
  position: relative;
  text-align:center;
  width:100%;
}

.overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  <!--background-color: #008CBA;-->
  overflow: hidden;
  width: 100%;
  height: 100%;
  transform: scale(0);
  transition: .3s ease;
}

.container:hover .overlay {
  transform: scale(1);
}

.overlayimage {
  color: white;
  font-size: 100px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.text {
  margin: 0% 5% 5% 5%;
}

.img
{
  display: inline;
}

.p {
  font-size: 30px;
  font-size: 3.5vw;
}

.subMenu{
  <!--border: 1px #00f solid;-->
  margin-left: 20px;
  list-style: none;
  columns: 300px;
  column-gap: 20px;
  column-fill: auto;
}


.subMenu li{
  <!--border: 1px #f00 solid;-->
  padding: 5px 0px;
  text-transform: none;
  font-size: 16px;
  color: #757575;
  -webkit-column-break-inside: avoid;
  page-break-inside: avoid;
  break-inside: avoid;
}

</style>

<header class="major">
	<h1> Meet The Team </h1>
  <!--p> [statement] </p-->
</header>

<div class="row">
  <div class="centerwrapper">
    <!-- Régis Pomès -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/Regis_Pomes.jpg">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/biography#regis_pomes" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/water2.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Régis Pomès</h3>
          <p class="title">Principal Investigator</p>
        </div>
    </div>
  </div>
</div>

<div class="row">

<div class="centerwrapper">
  <!-- JINGJING HUANG -->
  <div class="column">
    <div class="card card-deck">
      <div class="container">
        <img class="centered-and-cropped" src="/team/photos/Jingjing_Huang.jpg">
        <!-- OPTIONAL HOVER STUFF -->
        <div class="overlay">
          <a href="{{ "/team/biography/#jingjing_huang" | absolute_url }}">
            <img class="centered-and-cropped" src="/team/photos/default_mol.png">
          </a>
        </div>
        <!-- ENDS HERE -->
      </div>
        <h3 class="header-text">Jingjing<br>Huang</h3>
        <p class="title">PhD Candidate</p>
      </div>
  </div>

  <!-- Zhi Zeng -->
  <div class="column">
    <div class="card card-deck">
      <div class="container">
        <img class="centered-and-cropped" src="/team/photos/Zhi_Zeng.png">
        <!-- OPTIONAL HOVER STUFF -->
        <div class="overlay">
          <a href="{{ "/team/biography/#zhi_zeng" | absolute_url }}">
            <img class="centered-and-cropped" src="/team/photos/default_mol.png">
          </a>
        </div>
        <!-- ENDS HERE -->
      </div>
        <h3 class="header-text">Zhi<br>Zeng</h3>
        <p class="title">PhD Candidate</p>
      </div>
  </div>


    <!-- Quang Huynh -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/default.png">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/default_mol.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Quang<br>Huynh</h3>
          <p class="title">MSc</p>
        </div>
    </div>

    <!-- Ananya Srivastava -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/Ananya_Srivastava.jpg">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/biography/#ananya_srivastava" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/default_mol.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Ananya<br>Srivastava</h3>
          <p class="title">MSc Candidate</p>
        </div>
    </div>

    <!-- Anna Liang -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/Anna_Liang.jpeg">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay" style="clip-path: inset(0px 0px 0px 0px)">
            <a href="{{ "/team/biography/#anna_liang" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/LIMP2.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Anna<br>Liang</h3>
          <p class="title">MSc Candidate</p>
        </div>
    </div>

    <!-- Andrea Guljas -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/default.png">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/biography/#andrea_guljas" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/default_mol.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Andrea<br>Guljas</h3>
          <p class="title">MSc Candidate</p>
        </div>
    </div>

    <!-- Lamia Hossain -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/default.png">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/default_mol.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Lamia<br>Hossain</h3>
          <p class="title">MSc Candidate</p>
        </div>
    </div>

    <!-- Richard Banh -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/Richard_Banh.png">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/HV1.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Richard<br>Banh</h3>
          <p class="title">MSc Candidate</p>
        </div>
    </div>

    <!-- Fangwei Chang -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/default.png">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/default_mol.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Fangwei<br>Chang</h3>
          <p class="title">Researcher</p>
        </div>
    </div>

    <!-- Fei Wang -->
    <div class="column">
      <div class="card card-deck">
        <div class="container">
          <img class="centered-and-cropped" src="/team/photos/default.png">
          <!-- OPTIONAL HOVER STUFF -->
          <div class="overlay">
            <a href="{{ "/team/" | absolute_url }}">
              <img class="centered-and-cropped" src="/team/photos/default_mol.png">
            </a>
          </div>
          <!-- ENDS HERE -->
        </div>
          <h3 class="header-text">Fei<br>Wang</h3>
          <p class="title">Researcher</p>
        </div>
    </div>
  </div>
</div>

<header class="major">
	<h1> Alumni </h1>
</header>

<ul class="subMenu">
  <li><a href="">Aditi Ramesh - MSc</a></li>
  <li><a href="">Adrian Levine - Researcher</a></li>
  <li><a href="">Ana Nikolic - Researcher</a></li>
  <li><a href="">Ching-Hsing Yu - Researcher</a></li>
  <li><a href="">Christopher Ing - PhD</a></li>
  <li><a href="">Chris Madill - PhD</a></li>
  <li><a href="">Chris Neale - PhD</a></li>
  <li><a href="">David Caplan - MSc</a></li>
  <li><a href="">Elisa Fadda - Postdoctoral Fellow</a></li>
  <li><a href="">Ellen Li - Researcher</a></li>
  <li><a href="">Grace Li - Ph.D.</a></li>
  <li><a href="">Howard Wu - Researcher</a></li>
  <li><a href="">John Holyoake - Postdoctoral Fellow</a></li>
  <li><a href="">Joshua Charkow - Researcher</a></li>
  <li><a href="">Kethika Kulleperuma - PhD</a></li>
  <li><a href="">Loan Huynh - Postdoctoral Fellow</a></li>
  <li><a href="">Marty Kurylowicz - PhD</a></li>
  <li><a href="">Nick Wang - Researcher</a></li>
  <li><a href="">Nilu Chakrabarti - Postdoctoral Fellow</a></li>
  <li><a href="">Nisha Patel - Researcher</a></li>
  <li><a href="">Rachel Ko - Researcher</a></li>
  <li><a href="">Rowan Henry - MSc</a></li>
  <li><a href="">Sarah Rauscher - PhD</a></li>
  <li><a href="">Stéphanie Baud - Postdoctoral Fellow</a></li>
  <li><a href="">Tom Rodinger - PhD</a></li>
  <li><a href="">Zhuyi Xue - MSc</a></li>
</ul>

<h2 style="text-align: left;"> Positions </h2>
<p>
  We are always interested in talking to prospective students.
  Canadian undergraduates with backgrounds in chemistry, biology, physics and computer science are urged to apply to <b><a href="http://www.nserc-crsng.gc.ca/Students-Etudiants/UG-PC/USRA-BRPC_eng.asp"> NSERC USRA </a></b> for summer internships in our group.
  Graduate students with experience in computational biology, chemistry, and physics are encouraged to apply to <b><a href="http://www.nserc-crsng.gc.ca/Students-Etudiants/PG-CS/index_eng.asp">NSERC PGS/CGS</a></b> and <b><a href="https://www.osap.gov.on.ca/OSAPPortal/en/A-ZListofAid/PRDR019245.html">OGS </a></b>.
  Postdoctoral Fellows with experience in molecular dynamics and biomolecular simulation should consider an application for a <b><a href="http://banting.fellowships-bourses.gc.ca/en/home-accueil.html">Banting Fellowship</a></b>.
</p>

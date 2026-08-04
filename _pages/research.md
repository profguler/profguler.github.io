---
permalink: /research/
title: "Research"
author_profile: true
---

<!-- ========================================================= -->
<!--                     PAGE CSS                              -->
<!-- ========================================================= -->

<style>

/* ========================================================= */
/*                     INTRODUCTION                           */
/* ========================================================= */

.research-intro {
  max-width: 900px;
  margin-bottom: 2rem;
}

.research-intro p {
  margin: 0 0 0.8rem;
  font-size: 1rem;
  line-height: 1.7;
  color: #555;
}

/* ========================================================= */
/*                  RESEARCH GRID                             */
/* ========================================================= */

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0,1fr));
  gap: 1.25rem;
  max-width: 950px;
}

/* ========================================================= */
/*                  RESEARCH CARDS                            */
/* ========================================================= */

.research-card{
  display:flex;
  flex-direction:column;
  min-height:180px;
  padding:0;
  overflow:hidden;
  border:1px solid #d8d8d8;
  border-radius:14px;
  background:#ffffff;
  color:inherit !important;
  text-decoration:none !important;
  box-sizing:border-box;
  transition:
    transform .2s ease,
    box-shadow .2s ease,
    border-color .2s ease;
}

.research-card-image{
  display:block;
  width:100%;
  height:175px;
  object-fit:contain;
  object-position:center;
  background:#ffffff;
  border-bottom:1px solid #e5e5e5;
}

.research-card-body{
  display:flex;
  flex:1;
  flex-direction:column;
  padding:1.25rem;
}

.research-card h2{
  margin:0 0 .7rem;
  font-size:1.15rem;
  line-height:1.3;
  color:#2c7fa8;
}

.research-card p{
  margin:0;
  font-size:.94rem;
  line-height:1.55;
  color:#555;
}

.research-link{
  margin-top:auto;
  padding-top:1rem;
  font-size:.92rem;
  font-weight:600;
  color:#2c7fa8;
}

/* ========================================================= */
/*                  PUBLICATIONS CARD                         */
/* ========================================================= */

.publications-card{
  grid-column:1 / -1;
  min-height:120px;
}

/* ========================================================= */
/*                     CARD EFFECTS                           */
/* ========================================================= */

.research-card:focus,
.research-card:active{
  outline:none;
}

@media (hover:hover){

.research-card:hover{
  transform:translateY(-3px);
  border-color:#2c7fa8;
  box-shadow:0 6px 18px rgba(0,0,0,.10);
}

}

/* ========================================================= */
/*                   RESPONSIVE DESIGN                        */
/* ========================================================= */

@media screen and (max-width:700px){

.research-grid{
grid-template-columns:1fr;
}

.research-card{
min-height:auto;
}

.research-card-image{
height:auto;
max-height:330px;
object-fit:contain;
}

.publications-card{
grid-column:auto;
}

}

</style>

<!-- ========================================================= -->
<!--                     INTRODUCTION                          -->
<!-- ========================================================= -->

<div class="research-intro">

<p>

My research integrates analytical mechanics, computational mechanics, finite element analysis, and engineering simulation to address challenging problems in contact mechanics, thin films, crashworthiness, thermal sciences, structural stability, and engineering design.

</p>

<p>

The research activities are organized into six principal themes.

</p>

</div>

<!-- ========================================================= -->
<!--                    RESEARCH GRID                          -->
<!-- ========================================================= -->

<div class="research-grid">

<!-- ========================================================= -->
<!--      CARD 1 : COMPUTATIONAL CONTACT MECHANICS             -->
<!-- ========================================================= -->

<a class="research-card" href="/research/contact-mechanics/">

<img
class="research-card-image"
src="/images/Pin_hole_contact.png"
alt="Rigid pin in a couple-stress elastic plane">

<div class="research-card-body">

<h2>Computational Contact Mechanics</h2>

<p>

Analytical and computational formulations for contact problems involving elastic, graded, layered, and generalized continuum materials, including frictional contact and pin-loaded structures.

</p>

<div class="research-link">

Explore research →

</div>

</div>

</a>

<!-- ========================================================= -->
<!--    CARD 2 : THIN FILM MECHANICS & SURFACE EFFECTS         -->
<!-- ========================================================= -->

<a class="research-card" href="/research/thin-film-mechanics/">

<img
class="research-card-image"
src="/images/Thin_film_graded_EFM.png"
alt="Thin-film system with graded bonding layer">

<div class="research-card-body">

<h2>Thin Film Mechanics and Surface Effects</h2>

<p>

Buckling, delamination, cohesive-zone modeling, surface elasticity, graded bonding layers, and size-dependent behavior of thin-film/substrate systems.

</p>

<div class="research-link">

Explore research →

</div>

</div>

</a>

<!-- ========================================================= -->
<!--  CARD 3 : CRASHWORTHINESS & LIGHTWEIGHT STRUCTURES        -->
<!-- ========================================================= -->

<a class="research-card" href="/research/crashworthiness/">
  
<img
class="research-card-image"
src="/images/Crashbox_corrugation_JBSME.png"
alt="Thin-film system with graded bonding layer">

<div class="research-card-body">

<h2>Crashworthiness and Lightweight Structures</h2>

<p>

Energy absorption, thin-walled structures, vehicle safety, structural optimization, multi-cell concepts, and simulation-driven lightweight design.

</p>

<div class="research-link">

Explore research →

</div>

</div>

</a>

<!-- ========================================================= -->
<!--      CARD 4 : THERMAL CONTACT RESISTANCE                  -->
<!-- ========================================================= -->

<a class="research-card" href="/research/thermal-contact/">

<img
  class="research-card-image"
  src="/images/Asperity_IJSS.png"
  alt="Rough surface contact and asperity heat transfer"
>

<div class="research-card-body">

<h2>Thermal Contact Resistance</h2>

<p>

Heat transfer across rough interfaces, thermo-elastoplastic contact, surface morphology, and multiscale computational modeling of thermal interfaces.

</p>

<div class="research-link">

Explore research →

</div>

</div>

</a>

<!-- ========================================================= -->
<!--      CARD 5 : STRUCTURAL STABILITY & BUCKLING             -->
<!-- ========================================================= -->

<a class="research-card" href="/research/structural-stability/">

<img
  class="research-card-image"
  src="/images/Vierendeel_JBE.png"
  alt="Vierendeel mechanism in a perforated beam"
>

<div class="research-card-body">

<h2>Structural Stability and Buckling</h2>

<p>

Buckling and post-buckling behavior of thin-walled members, corrugated beams, aluminum sections, layered structures, and imperfect structural systems.

</p>

<div class="research-link">

Explore research →

</div>

</div>

</a>

<!-- ========================================================= -->
<!--   CARD 6 : COMPUTATIONAL MECHANICS & FEA                  -->
<!-- ========================================================= -->

<a class="research-card" href="/research/computational-mechanics/">

<div class="research-card-body">

<h2>Computational Mechanics and Finite Element Analysis</h2>

<p>

Finite element methods, nonlinear simulation, numerical modeling, engineering software, verification, optimization, and simulation-driven engineering design.

</p>

<div class="research-link">

Explore research →

</div>

</div>

</a>

<!-- ========================================================= -->
<!--                CARD 7 : PUBLICATIONS                      -->
<!-- ========================================================= -->

<a class="research-card publications-card" href="/publications/">

<div class="research-card-body">

<h2>Publications</h2>

<p>

Peer-reviewed journal articles, conference papers, and selected scholarly contributions across computational mechanics, contact mechanics, structural engineering, crashworthiness, and advanced materials.

</p>

<div class="research-link">

View publications →

</div>

</div>

</a>

</div>

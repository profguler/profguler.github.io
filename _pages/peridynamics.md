---
permalink: /research/peridynamics/
title: "Peridynamics and Computational Fracture"
author_profile: true
---

<!-- ========================================================= -->
<!--                    PAGE STYLES                            -->
<!-- ========================================================= -->

<style>

/* ========================================================= */
/*                    HERO IMAGE                              */
/* ========================================================= */

.research-banner{
  width:100%;
  max-width:900px;
  margin:0 0 2rem 0;
  border:1px solid #dddddd;
  border-radius:12px;
  overflow:hidden;
  background:#ffffff;
}

.research-banner img{
  display:block;
  width:100%;
  height:auto;
}

.figure-caption{
  max-width:900px;
  margin:-1rem auto 2rem;
  text-align:center;
  font-size:0.9rem;
  font-style:italic;
  line-height:1.5;
  color:#666;
}

/* ========================================================= */
/*                    HIGHLIGHTS                              */
/* ========================================================= */

.research-highlights{
  display:grid;
  grid-template-columns:repeat(3, minmax(0, 1fr));
  gap:18px;
  max-width:900px;
  margin-bottom:2.5rem;
}

.highlight-box{
  padding:18px;
  border:1px solid #dddddd;
  border-radius:12px;
  background:#fafafa;
  text-align:center;
  box-sizing:border-box;
}

.highlight-title{
  margin-bottom:8px;
  font-size:1rem;
  font-weight:700;
  color:#2c7fa8;
}

.highlight-text{
  font-size:0.93rem;
  line-height:1.6;
  color:#555;
}

/* ========================================================= */
/*                    CONTENT SECTIONS                        */
/* ========================================================= */

.research-section{
  display:block;
  width:100%;
  max-width:900px;
  clear:both;
  margin-bottom:2.5rem;
  box-sizing:border-box;
}

.research-section h2{
  margin:0 0 0.75rem;
  padding-bottom:0.35rem;
  border-bottom:2px solid #eeeeee;
  color:#2c7fa8;
}

.research-section p,
.research-section li{
  font-size:1rem;
  line-height:1.75;
  color:#555;
}

/* ========================================================= */
/*                    RESEARCH TOPICS                         */
/* ========================================================= */

.research-topics{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  width:100%;
  margin-top:1rem;
}

.research-topic{
  display:inline-block;
  padding:8px 15px;
  border:1px solid #d7e7f0;
  border-radius:999px;
  background:#eef6fb;
  color:#2c7fa8;
  font-size:0.9rem;
  font-weight:600;
  line-height:1.3;
}

/* ========================================================= */
/*                    PUBLICATIONS                            */
/* ========================================================= */

.research-publication{
  position:relative;
  z-index:1;
  margin-bottom:1.5rem;
  padding-bottom:1rem;
  border-bottom:1px solid #eeeeee;
}

.research-publication-title{
  position:relative;
  z-index:2;
  margin-bottom:0.35rem;
  font-weight:700;
  line-height:1.5;
}

.research-publication-title a{
  position:relative;
  z-index:3;
  display:inline;
  color:#2c7fa8 !important;
  text-decoration:none !important;
  cursor:pointer;
  pointer-events:auto !important;
}

.research-publication-title a:hover{
  color:#1f5f80 !important;
  text-decoration:underline !important;
}

.research-publication-title a:focus{
  outline:2px solid #2c7fa8;
  outline-offset:3px;
}

.research-publication-authors{
  color:#555;
  line-height:1.6;
}

.research-publication-journal{
  color:#666;
  font-style:italic;
  line-height:1.6;
}

/* ========================================================= */
/*                    BACK BUTTON                             */
/* ========================================================= */

.back-button{
  display:inline-block;
  margin-top:1rem;
  padding:10px 24px;
  border:1px solid #2c7fa8;
  border-radius:999px;
  color:#2c7fa8;
  text-decoration:none;
  font-weight:600;
  transition:0.2s;
}

.back-button:hover{
  background:#2c7fa8;
  color:#ffffff;
  text-decoration:none;
}

/* ========================================================= */
/*                    MOBILE DESIGN                           */
/* ========================================================= */

@media screen and (max-width:700px){

  .research-highlights{
    grid-template-columns:1fr;
    gap:12px;
  }

  .research-topic{
    font-size:0.86rem;
  }

}

</style>

<!-- ========================================================= -->
<!--                    HERO IMAGE                             -->
<!-- ========================================================= -->

<div class="research-banner">

  <img
    src="/images/Peridynamics_DCB.png"
    alt="Peridynamic double cantilever beam model"
  >

</div>

<div class="figure-caption">

Peridynamic representation of a double cantilever beam with an initial crack and interface region for simulating delamination and crack propagation.

</div>

<!-- ========================================================= -->
<!--                    HIGHLIGHTS                             -->
<!-- ========================================================= -->

<div class="research-highlights">

  <div class="highlight-box">

    <div class="highlight-title">
      Nonlocal Mechanics
    </div>

    <div class="highlight-text">
      Development of peridynamic formulations for solids containing cracks, interfaces, and other discontinuities.
    </div>

  </div>

  <div class="highlight-box">

    <div class="highlight-title">
      Computational Fracture
    </div>

    <div class="highlight-text">
      Simulation of crack initiation, crack growth, branching, and delamination without remeshing.
    </div>

  </div>

  <div class="highlight-box">

    <div class="highlight-title">
      Composite Structures
    </div>

    <div class="highlight-text">
      Modeling of orthotropic materials, laminated composites, and interface failure using nonlocal mechanics.
    </div>

  </div>

</div>
<!-- ========================================================= -->
<!--                     OVERVIEW                              -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Overview</h2>

  <p>
  My research in peridynamics focuses on the development and application of nonlocal computational methods for fracture, damage, and failure analysis. Unlike classical continuum mechanics, peridynamic theory replaces spatial derivatives with integral equations, allowing discontinuities such as cracks to emerge naturally without requiring special crack-tip treatments or remeshing.
  </p>

  <p>
  The research combines theoretical formulation, numerical implementation, and computational simulation to investigate fracture in isotropic and orthotropic materials, composite laminates, layered structures, and engineering components. Particular emphasis is placed on crack initiation, crack propagation, delamination, and dynamic fracture, where conventional finite element methods often require sophisticated remeshing or enrichment techniques.
  </p>

</div>

<!-- ========================================================= -->
<!--                  RESEARCH TOPICS                          -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Research Topics</h2>

  <div class="research-topics">

    <span class="research-topic">Peridynamic Theory</span>

    <span class="research-topic">Computational Fracture Mechanics</span>

    <span class="research-topic">Crack Initiation</span>

    <span class="research-topic">Crack Propagation</span>

    <span class="research-topic">Composite Delamination</span>

    <span class="research-topic">Dynamic Fracture</span>

    <span class="research-topic">Double Cantilever Beam Analysis</span>

    <span class="research-topic">Orthotropic Materials</span>

    <span class="research-topic">Mindlin Plate Theory</span>

    <span class="research-topic">Intersonic Shear Cracks</span>

    <span class="research-topic">Nonlocal Continuum Mechanics</span>

    <span class="research-topic">Layered Composite Structures</span>

    <span class="research-topic">Interface Elements</span>

    <span class="research-topic">Finite Element–Peridynamic Coupling</span>

    <span class="research-topic">Scientific Computing</span>

  </div>

</div>

<!-- ========================================================= -->
<!--             REPRESENTATIVE CONTRIBUTIONS                  -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Representative Contributions</h2>

  <ul>

    <li>
      Developed a peridynamic formulation for orthotropic Mindlin plates subjected to bending, extending nonlocal mechanics to laminated plate structures.
    </li>

    <li>
      Developed computational models for Mode-I crack growth in double cantilever beam specimens using bond-based peridynamics.
    </li>

    <li>
      Investigated intersonic shear crack propagation using peridynamic theory to study high-speed fracture phenomena.
    </li>

    <li>
      Implemented peridynamic algorithms for composite delamination and interface-damage evolution.
    </li>

    <li>
      Integrated peridynamic formulations with finite element techniques to improve computational efficiency for large structural models.
    </li>

    <li>
      Applied nonlocal computational methods to fracture problems without requiring predefined crack paths or remeshing.
    </li>

  </ul>

</div>

<!-- ========================================================= -->
<!--                  CURRENT RESEARCH                         -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Current Research</h2>

  <p>
  Current research focuses on computational fracture of layered and composite structures using nonlocal continuum mechanics. Ongoing work investigates efficient numerical implementation, improved constitutive formulations, and hybrid finite element–peridynamic approaches for predicting crack initiation and delamination in engineering materials.
  </p>

  <p>
  Additional directions include the application of peridynamic methods to impact-damaged composites, structural plates, interacting fracture modes, fatigue crack growth, and large-scale engineering simulations.
  </p>

</div>
<!-- ========================================================= -->
<!--               REPRESENTATIVE PUBLICATIONS                 -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Representative Publications</h2>

  <!-- ------------------------------------------------------- -->
  <!-- PUBLICATION 1: DOUBLE CANTILEVER BEAM                   -->
  <!-- ------------------------------------------------------- -->

  <div class="research-publication">

    <div class="research-publication-title">

      <a
        href="https://doi.org/10.1016/j.compstruct.2022.116050"
        target="_blank"
        rel="noopener noreferrer"
      >
        Crack propagation in the double cantilever beam using peridynamic theory
      </a>

    </div>

    <div class="research-publication-authors">
      U. Yolum, M. O. Bozkurt, E. Gök, D. Coker, and M. A. Güler
    </div>

    <div class="research-publication-journal">
      Composite Structures, 299, 116050, 2022
    </div>

  </div>

  <!-- ------------------------------------------------------- -->
  <!-- PUBLICATION 2: INTERSONIC SHEAR CRACK                   -->
  <!-- ------------------------------------------------------- -->

  <div class="research-publication">

    <div class="research-publication-title">

      <a
        href="https://doi.org/10.1007/s10704-021-00520-3"
        target="_blank"
        rel="noopener noreferrer"
      >
        Intersonic shear crack propagation using peridynamic theory
      </a>

    </div>

    <div class="research-publication-authors">
      U. Yolum, D. Coker, and M. A. Güler
    </div>

    <div class="research-publication-journal">
      International Journal of Fracture, 228(1), 103–126, 2021
    </div>

  </div>

  <!-- ------------------------------------------------------- -->
  <!-- PUBLICATION 3: ORTHOTROPIC MINDLIN PLATE                -->
  <!-- ------------------------------------------------------- -->

  <div class="research-publication">

    <div class="research-publication-title">

      <a
        href="https://doi.org/10.1177/1081286519873694"
        target="_blank"
        rel="noopener noreferrer"
      >
        On the peridynamic formulation for an orthotropic Mindlin plate under bending
      </a>

    </div>

    <div class="research-publication-authors">
      U. Yolum and M. A. Güler
    </div>

    <div class="research-publication-journal">
      Mathematics and Mechanics of Solids, 25(2), 263–287, 2020
    </div>

  </div>

</div>
<!-- ========================================================= -->
<!--                    COLLABORATIONS                         -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Collaborations</h2>

  <p>
  This research has been carried out in collaboration with researchers specializing in computational mechanics, fracture mechanics, peridynamic theory, composite materials, and finite element analysis. These collaborations have contributed to the development of novel nonlocal formulations for fracture and delamination, efficient numerical implementations, and applications to layered composites and engineering structures.
  </p>

</div>

<!-- ========================================================= -->
<!--                    FUTURE DIRECTIONS                      -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Future Directions</h2>

  <p>
  Future research will focus on hybrid finite element–peridynamic formulations, multiscale fracture modeling, fatigue crack growth, impact-induced damage in composite structures, adaptive numerical algorithms, and AI-assisted computational fracture mechanics. Particular emphasis will be placed on improving computational efficiency while preserving the predictive capabilities of nonlocal continuum models for large-scale engineering applications.
  </p>

</div>

<!-- ========================================================= -->
<!--                    BACK BUTTON                            -->
<!-- ========================================================= -->

<a class="back-button" href="/research/">

  ← Back to Research

</a>

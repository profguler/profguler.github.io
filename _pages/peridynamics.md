---
permalink: /research/peridynamics/
title: "Peridynamics and Computational Fracture"
author_profile: true
---

<!-- ========================================================= -->
<!--                         PAGE CSS                          -->
<!-- ========================================================= -->

<style>

/* ========================================================= */
/*                    HERO FIGURE                             */
/* ========================================================= */

.research-banner{
  width:100%;
  max-width:900px;
  margin:0 0 2rem;
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
  font-size:0.9rem;
  font-style:italic;
  text-align:center;
  color:#666;
}

/* ========================================================= */
/*                    HIGHLIGHTS                              */
/* ========================================================= */

.research-highlights{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:18px;
  max-width:900px;
  margin-bottom:2rem;
}

.highlight-box{
  padding:18px;
  border:1px solid #dddddd;
  border-radius:12px;
  background:#fafafa;
  text-align:center;
}

.highlight-title{
  margin-bottom:8px;
  color:#2c7fa8;
  font-size:1rem;
  font-weight:700;
}

.highlight-text{
  color:#555;
  font-size:0.92rem;
  line-height:1.5;
}

/* ========================================================= */
/*                    CONTENT SECTIONS                        */
/* ========================================================= */

.research-section{
  max-width:900px;
  margin-bottom:2.5rem;
}

.research-section h2{
  margin-bottom:0.75rem;
  padding-bottom:0.35rem;
  border-bottom:2px solid #eeeeee;
  color:#2c7fa8;
}

.research-section p,
.research-section li{
  color:#555;
  font-size:1rem;
  line-height:1.75;
}

.research-topics{
  columns:2;
  column-gap:3rem;
}

.research-topics ul{
  margin-top:0;
}

/* ========================================================= */
/*                    PUBLICATIONS                            */
/* ========================================================= */

.publication{
  margin-bottom:1.3rem;
  padding-bottom:1rem;
  border-bottom:1px solid #eeeeee;
}

.publication-title{
  color:#2c7fa8;
  font-weight:700;
}

.publication-authors{
  color:#555;
}

.publication-journal{
  color:#666;
  font-style:italic;
}

.publication-doi a{
  color:#2c7fa8;
  text-decoration:none;
}

.publication-doi a:hover{
  text-decoration:underline;
}

/* ========================================================= */
/*                    BACK BUTTON                             */
/* ========================================================= */

.back-button{
  display:inline-block;
  margin-top:1rem;
  padding:10px 22px;
  border:1px solid #2c7fa8;
  border-radius:999px;
  color:#2c7fa8;
  font-weight:600;
  text-decoration:none;
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
  }

  .research-topics{
    columns:1;
  }

}

</style>

<!-- ========================================================= -->
<!--                    HERO IMAGE                             -->
<!-- ========================================================= -->

<div class="research-banner">

  <img
    src="/images/Peridynamics_DCB.png"
    alt="Peridynamic model of a double cantilever beam"
  >

</div>

<div class="figure-caption">

Peridynamic representation of a double cantilever beam containing an initial crack and interface elements for delamination and crack-growth analysis.

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
      Peridynamic formulations for solids containing cracks, interfaces, and discontinuities.
    </div>

  </div>

  <div class="highlight-box">

    <div class="highlight-title">
      Computational Fracture
    </div>

    <div class="highlight-text">
      Simulation of crack initiation, propagation, branching, and delamination without remeshing.
    </div>

  </div>

  <div class="highlight-box">

    <div class="highlight-title">
      Composite Failure
    </div>

    <div class="highlight-text">
      Modeling of layered composites, orthotropic plates, and interface damage under complex loading.
    </div>

  </div>

</div>

<!-- ========================================================= -->
<!--                    OVERVIEW                               -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Overview</h2>

  <p>
  My research in peridynamics focuses on the development and application of nonlocal computational methods for fracture, delamination, and failure analysis. Unlike classical continuum formulations, peridynamic theory permits discontinuities to develop naturally within the governing equations, making it especially suitable for problems involving crack initiation and propagation.
  </p>

  <p>
  This work combines peridynamic formulations, numerical implementation, finite element coupling, and computational fracture mechanics to investigate failure in isotropic, orthotropic, composite, and layered structures. Applications include double cantilever beams, plates under bending, intersonic crack propagation, composite delamination, and damage evolution in engineering materials.
  </p>

</div>

<!-- ========================================================= -->
<!--                    RESEARCH TOPICS                        -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Research Topics</h2>

  <div class="research-topics">

    <ul>

      <li>Peridynamic theory</li>

      <li>Computational fracture mechanics</li>

      <li>Crack initiation and propagation</li>

      <li>Composite delamination</li>

      <li>Double cantilever beam analysis</li>

      <li>Orthotropic materials</li>

      <li>Mindlin plate theory</li>

      <li>Intersonic shear cracks</li>

      <li>Ductile fracture</li>

      <li>Layered composites</li>

      <li>Interface elements</li>

      <li>Nonlocal continuum mechanics</li>

      <li>Abaqus implementation</li>

      <li>LS-DYNA implementation</li>

      <li>Finite element–peridynamic coupling</li>

    </ul>

  </div>

</div>

<!-- ========================================================= -->
<!--               REPRESENTATIVE CONTRIBUTIONS                -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Representative Contributions</h2>

  <ul>

    <li>
    Developed peridynamic formulations for orthotropic plates subjected to bending.
    </li>

    <li>
    Modeled Mode I delamination growth in double cantilever beam specimens.
    </li>

    <li>
    Investigated intersonic shear crack propagation using nonlocal theory.
    </li>

    <li>
    Applied peridynamics to layered composite failure and interface damage.
    </li>

    <li>
    Implemented peridynamic models in finite element environments including Abaqus and LS-DYNA.
    </li>

    <li>
    Studied crack-growth behavior without requiring predefined crack paths or continual remeshing.
    </li>

  </ul>

</div>

<!-- ========================================================= -->
<!--                    CURRENT RESEARCH                       -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Current Research</h2>

  <p>
  Current work focuses on improving computational strategies for fracture and interface failure in composite and layered structures. Particular attention is given to efficient numerical implementation, coupling with finite element methods, and the accurate representation of delamination and bending-induced failure.
  </p>

  <p>
  Ongoing directions also include the use of peridynamic models for impact-damaged composites, structural plates, and problems involving interacting fracture modes.
  </p>

</div>

<!-- ========================================================= -->
<!--               REPRESENTATIVE PUBLICATIONS                 -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Representative Publications</h2>

  <div class="publication">

    <div class="publication-title">
      Crack propagation in the double cantilever beam using peridynamic theory
    </div>

    <div class="publication-authors">
      U. Yolum, M. O. Bozkurt, E. Gök, D. Coker, and M. A. Güler
    </div>

    <div class="publication-journal">
      Composite Structures, 2022, 116050
    </div>

  </div>

  <div class="publication">

    <div class="publication-title">
      Intersonic shear crack propagation using peridynamic theory
    </div>

    <div class="publication-authors">
      U. Yolum, D. Coker, and M. A. Güler
    </div>

    <div class="publication-journal">
      International Journal of Fracture, 228, 103–126, 2021
    </div>

  </div>

  <div class="publication">

    <div class="publication-title">
      On the peridynamic formulation for an orthotropic Mindlin plate under bending
    </div>

    <div class="publication-authors">
      U. Yolum and M. A. Güler
    </div>

    <div class="publication-journal">
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
  This research has involved collaboration with researchers specializing in peridynamics, computational fracture mechanics, composite materials, nonlinear dynamics, and finite element implementation.
  </p>

</div>

<!-- ========================================================= -->
<!--                    FUTURE DIRECTIONS                      -->
<!-- ========================================================= -->

<div class="research-section">

  <h2>Future Directions</h2>

  <p>
  Future research will focus on computationally efficient peridynamic formulations, hybrid finite element–peridynamic methods, multiscale damage modeling, fatigue crack growth, and data-assisted fracture prediction. These developments will support applications in composite structures, aerospace systems, impact-damaged components, and advanced layered materials.
  </p>

</div>

<!-- ========================================================= -->
<!--                    BACK BUTTON                            -->
<!-- ========================================================= -->

<a class="back-button" href="/research/">

  ← Back to Research

</a>

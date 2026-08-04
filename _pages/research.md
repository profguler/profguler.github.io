---
permalink: /research/
title: "Research"
author_profile: true
---

<style>
.research-intro {
  margin-bottom: 2rem;
  max-width: 900px;
}

.research-intro p {
  font-size: 1rem;
  line-height: 1.7;
  color: #555;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
  max-width: 950px;
}

.research-card {
  display: flex;
  flex-direction: column;
  min-height: 180px;
  padding: 0;
  overflow: hidden;
  border: 1px solid #d8d8d8;
  border-radius: 14px;
  background: #ffffff;
  text-decoration: none !important;
  box-sizing: border-box;
  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease,
    border-color 0.2s ease;
}

.research-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.10);
  border-color: #2c7fa8;
}

.research-card h2 {
  margin-top: 0;
  margin-bottom: 0.7rem;
  font-size: 1.15rem;
  line-height: 1.3;
  color: #2c7fa8;
}

.research-card p {
  margin: 0;
  font-size: 0.94rem;
  line-height: 1.55;
  color: #555;
}

  .research-card-image {
  width: 100%;
  height: 210px;
  object-fit: contain;
  object-position: center;
  display: block;
  background: #ffffff;
  border-bottom: 1px solid #e5e5e5;
}

.research-card-body {
  display: flex;
  flex-direction: column;
  flex: 1;
  padding: 1.25rem;
}

.research-link {
  margin-top: auto;
  padding-top: 1rem;
  font-size: 0.92rem;
  font-weight: 600;
  color: #2c7fa8;
}

.publications-card {
  grid-column: 1 / -1;
  min-height: 120px;
}

@media screen and (max-width: 700px) {
  .research-grid {
    grid-template-columns: 1fr;
  }

  .publications-card {
    grid-column: auto;
  }

  .research-card {
    min-height: auto;
  }
}
</style>

<div class="research-intro">

My research integrates analytical mechanics, computational mechanics, finite element analysis, and engineering simulation to address challenging problems in contact mechanics, thin films, crashworthiness, thermal sciences, structural stability, and engineering design.

The research activities are organized into six principal themes.

</div>

<div class="research-grid">

<a class="research-card" href="/research/contact-mechanics/">

<img
  class="research-card-image"
  src="/images/Pin_hole_contact.png"
  alt="Rigid pin in a couple-stress elastic plane"
>

<div class="research-card-body">

<h2>Computational Contact Mechanics</h2>

<p>
Analytical and computational formulations for contact problems involving elastic, graded, layered, and generalized continuum materials, including frictional contact and pin-loaded structures.
</p>

<div class="research-link">Explore research →</div>

</div>

</a>

<a class="research-card" href="/research/thin-film-mechanics/">
<div>
<h2>Thin Film Mechanics and Surface Effects</h2>
<p>
Buckling, delamination, cohesive-zone modeling, surface elasticity, and size-dependent behavior of thin films and layered material systems.
</p>
</div>
<div class="research-link">Learn more →</div>
</a>

<a class="research-card" href="/research/crashworthiness/">
<div>
<h2>Crashworthiness and Lightweight Structures</h2>
<p>
Energy absorption, thin-walled structures, vehicle safety, structural optimization, multi-cell concepts, and simulation-driven lightweight design.
</p>
</div>
<div class="research-link">Learn more →</div>
</a>

<a class="research-card" href="/research/thermal-contact/">
<div>
<h2>Thermal Contact Resistance</h2>
<p>
Heat transfer across rough interfaces, thermo-elastoplastic contact, surface morphology, and multiscale computational modeling of thermal interfaces.
</p>
</div>
<div class="research-link">Learn more →</div>
</a>

<a class="research-card" href="/research/structural-stability/">
<div>
<h2>Structural Stability and Buckling</h2>
<p>
Buckling and post-buckling behavior of thin-walled members, corrugated beams, aluminum sections, layered structures, and imperfect structural systems.
</p>
</div>
<div class="research-link">Learn more →</div>
</a>

<a class="research-card" href="/research/computational-mechanics/">
<div>
<h2>Computational Mechanics and Finite Element Analysis</h2>
<p>
Finite element methods, nonlinear simulation, numerical modeling, engineering software, verification, optimization, and simulation-driven engineering design.
</p>
</div>
<div class="research-link">Learn more →</div>
</a>

<a class="research-card publications-card" href="/publications/">
<div>
<h2>Publications</h2>
<p>
Peer-reviewed journal articles, conference papers, and selected scholarly contributions across computational mechanics, contact mechanics, structural engineering, and crashworthiness.
</p>
</div>
<div class="research-link">View publications →</div>
</a>

</div>

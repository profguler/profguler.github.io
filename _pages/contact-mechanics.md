---
permalink: /research/contact-mechanics/
title: "Computational Contact Mechanics"
author_profile: true
---

<!-- ========================================================= -->
<!--                     PAGE-SPECIFIC CSS                     -->
<!-- ========================================================= -->

<style>

/* ========================================================= */
/*                     PAGE WRAPPER                          */
/* ========================================================= */

.ccm-page {
  width: 100%;
  max-width: 900px;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* ========================================================= */
/*                     HERO IMAGE                            */
/* ========================================================= */

.ccm-banner {
  width: 100%;
  margin: 0 0 1rem 0;
  border: 1px solid #dddddd;
  border-radius: 12px;
  overflow: hidden;
  background: #ffffff;
  box-sizing: border-box;
}

.ccm-banner img {
  display: block;
  width: 100%;
  height: auto;
}

.ccm-caption {
  margin: 0 0 2rem 0;
  font-size: 0.9rem;
  font-style: italic;
  line-height: 1.5;
  text-align: center;
  color: #666666;
}

/* ========================================================= */
/*                     HIGHLIGHTS                            */
/* ========================================================= */

.ccm-highlights {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  width: 100%;
  margin: 0 0 2.5rem 0;
}

.ccm-highlight-box {
  padding: 18px;
  border: 1px solid #dddddd;
  border-radius: 12px;
  background: #fafafa;
  text-align: center;
  box-sizing: border-box;
}

.ccm-highlight-title {
  margin-bottom: 8px;
  color: #2c7fa8;
  font-size: 1rem;
  font-weight: 700;
}

.ccm-highlight-text {
  color: #555555;
  font-size: 0.93rem;
  line-height: 1.6;
}

/* ========================================================= */
/*                     CONTENT SECTIONS                      */
/* ========================================================= */

.ccm-section {
  display: block;
  width: 100%;
  margin: 0 0 2.5rem 0;
  clear: both;
  box-sizing: border-box;
}

.ccm-section h2 {
  margin: 0 0 0.85rem 0;
  padding: 0 0 0.35rem 0;
  border-bottom: 2px solid #eeeeee;
  color: #2c7fa8;
  font-size: 1.35rem;
  line-height: 1.3;
}

.ccm-section p {
  margin: 0 0 1rem 0;
  color: #555555;
  font-size: 1rem;
  line-height: 1.75;
}

.ccm-section ul {
  margin: 0.4rem 0 0 1.25rem;
  padding: 0;
}

.ccm-section li {
  margin-bottom: 0.55rem;
  color: #555555;
  font-size: 1rem;
  line-height: 1.65;
}

/* ========================================================= */
/*                     RESEARCH TOPICS                       */
/* ========================================================= */

.ccm-topics {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  width: 100%;
  margin-top: 1rem;
}

.ccm-topic {
  display: inline-block;
  padding: 8px 15px;
  border: 1px solid #d7e7f0;
  border-radius: 999px;
  background: #eef6fb;
  color: #2c7fa8;
  font-size: 0.9rem;
  font-weight: 600;
  line-height: 1.3;
  white-space: normal;
}

/* ========================================================= */
/*                     PUBLICATIONS                          */
/* ========================================================= */

.ccm-publication {
  width: 100%;
  margin-bottom: 1.4rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #eeeeee;
  box-sizing: border-box;
}

.ccm-publication:last-child {
  margin-bottom: 0;
}

.ccm-publication-title {
  margin-bottom: 0.35rem;
  font-weight: 700;
  line-height: 1.5;
}

.ccm-publication-title a {
  color: #2c7fa8 !important;
  text-decoration: none !important;
  cursor: pointer;
  pointer-events: auto;
}

.ccm-publication-title a:hover {
  color: #1f5f80 !important;
  text-decoration: underline !important;
}

.ccm-publication-title a:focus {
  outline: 2px solid #2c7fa8;
  outline-offset: 3px;
}

.ccm-publication-authors {
  margin-bottom: 0.15rem;
  color: #555555;
  line-height: 1.6;
}

.ccm-publication-journal {
  color: #666666;
  font-style: italic;
  line-height: 1.6;
}

/* ========================================================= */
/*                     BACK BUTTON                           */
/* ========================================================= */

.ccm-back-button {
  display: inline-block;
  margin-top: 0.5rem;
  padding: 10px 24px;
  border: 1px solid #2c7fa8;
  border-radius: 999px;
  color: #2c7fa8 !important;
  font-weight: 600;
  text-decoration: none !important;
  transition: background-color 0.2s ease, color 0.2s ease;
}

.ccm-back-button:hover {
  background: #2c7fa8;
  color: #ffffff !important;
  text-decoration: none !important;
}

/* ========================================================= */
/*                     MOBILE DESIGN                         */
/* ========================================================= */

@media screen and (max-width: 700px) {

  .ccm-highlights {
    grid-template-columns: 1fr;
    gap: 12px;
  }

  .ccm-topic {
    font-size: 0.86rem;
  }

  .ccm-section h2 {
    font-size: 1.2rem;
  }

}

</style>

<!-- ========================================================= -->
<!--                     PAGE CONTENT                         -->
<!-- ========================================================= -->

<div class="ccm-page">

<!-- ========================================================= -->
<!--                     HERO IMAGE                           -->
<!-- ========================================================= -->

<div class="ccm-banner">
  <img
    src="/images/Pin_hole_contact.png"
    alt="Rigid pin in a couple-stress elastic plane"
  >
</div>

<div class="ccm-caption">
  Rigid pin with radial clearance in a couple-stress elastic plane, illustrating the geometry and higher-order fields used in size-dependent pin–hole contact analysis.
</div>

<!-- ========================================================= -->
<!--                     HIGHLIGHTS                           -->
<!-- ========================================================= -->

<div class="ccm-highlights">

  <div class="ccm-highlight-box">
    <div class="ccm-highlight-title">Generalized Continua</div>
    <div class="ccm-highlight-text">
      Couple-stress elasticity and size-dependent contact mechanics for microstructured materials.
    </div>
  </div>

  <div class="ccm-highlight-box">
    <div class="ccm-highlight-title">Analytical &amp; Numerical Methods</div>
    <div class="ccm-highlight-text">
      Singular integral equations, dual-series formulations, spectral methods, and finite element verification.
    </div>
  </div>

  <div class="ccm-highlight-box">
    <div class="ccm-highlight-title">Engineering Applications</div>
    <div class="ccm-highlight-text">
      Mechanical joints, pin-loaded structures, coated solids, rolling contact, and layered materials.
    </div>
  </div>

</div>

<!-- ========================================================= -->
<!--                     OVERVIEW                             -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Overview</h2>

  <p>
    My research in computational contact mechanics focuses on developing analytical and computational formulations for engineering contact problems involving both classical elasticity and generalized continuum theories. Particular emphasis is placed on couple-stress elasticity, functionally graded materials, anisotropic and layered media, frictional contact, rolling contact, and pin-loaded structural connections.
  </p>

  <p>
    The research combines rigorous mathematical modeling with numerical algorithms and finite element simulations to investigate contact pressure, stress concentration, singular behavior, partial slip, and size-dependent mechanical response. These studies provide improved understanding of contact phenomena in mechanical joints, bearings, coatings, layered solids, and advanced microstructured materials.
  </p>

</div>

<!-- ========================================================= -->
<!--                     RESEARCH TOPICS                      -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Research Topics</h2>

  <div class="ccm-topics">

    <span class="ccm-topic">Computational Contact Mechanics</span>
    <span class="ccm-topic">Couple-Stress Elasticity</span>
    <span class="ccm-topic">Generalized Continuum Mechanics</span>
    <span class="ccm-topic">Pin–Hole Contact</span>
    <span class="ccm-topic">Mechanical Joints</span>
    <span class="ccm-topic">Functionally Graded Materials</span>
    <span class="ccm-topic">Layered and Coated Media</span>
    <span class="ccm-topic">Frictional Contact</span>
    <span class="ccm-topic">Partial Slip</span>
    <span class="ccm-topic">Rolling Contact</span>
    <span class="ccm-topic">Stress Singularities</span>
    <span class="ccm-topic">Analytical Elasticity</span>
    <span class="ccm-topic">Singular Integral Equations</span>
    <span class="ccm-topic">Dual-Series Equations</span>
    <span class="ccm-topic">Spectral Numerical Methods</span>
    <span class="ccm-topic">Finite Element Verification</span>

  </div>

</div>

<!-- ========================================================= -->
<!--                     REPRESENTATIVE CONTRIBUTIONS          -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Representative Contributions</h2>

  <ul>
    <li>
      Developed analytical formulations for pin-loaded holes with radial clearance in classical and couple-stress elasticity.
    </li>
    <li>
      Introduced curvature-compatible pin–hole contact formulations that permit transmission of couple tractions across the contact interface.
    </li>
    <li>
      Investigated size effects and stress redistribution in microstructured elastic media using intrinsic material length scales.
    </li>
    <li>
      Developed benchmark solutions for frictional contact involving functionally graded, orthotropic, monoclinic, and layered materials.
    </li>
    <li>
      Studied rolling contact, partial slip, stress singularities, and critical surface stresses relevant to fatigue and fracture.
    </li>
    <li>
      Validated analytical contact solutions through finite element simulations and independent limiting cases.
    </li>
  </ul>

</div>

<!-- ========================================================= -->
<!--                     CURRENT RESEARCH                     -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Current Research</h2>

  <p>
    Current research focuses on refined pin–hole contact formulations within couple-stress elasticity, including curvature compatibility, the transmission of couple tractions across the contact interface, and the influence of material characteristic length on contact angle, pressure, stress, and couple-stress fields.
  </p>

  <p>
    Ongoing work extends these formulations toward frictional full-slip contact, generalized loading, surface effects, and comparisons with classical elasticity. Further developments are aimed at mechanically consistent models for micro-scale joints, pivots, bearings, and other curved contact interfaces.
  </p>

</div>

<!-- ========================================================= -->
<!--                     REPRESENTATIVE PUBLICATIONS           -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Representative Publications</h2>

  <div class="ccm-publication">

    <div class="ccm-publication-title">
      <a
        href="https://doi.org/10.1016/j.ijsolstr.2026.114121"
        target="_blank"
        rel="noopener noreferrer"
      >
        Pin–hole contact with curvature-induced couple tractions in couple-stress elasticity
      </a>
    </div>

    <div class="ccm-publication-authors">
      E. Radi and M. A. Güler
    </div>

    <div class="ccm-publication-journal">
      International Journal of Solids and Structures, 114121, 2026
    </div>

  </div>

  <div class="ccm-publication">

    <div class="ccm-publication-title">
      <a
        href="https://doi.org/10.1016/j.ijengsci.2025.104454"
        target="_blank"
        rel="noopener noreferrer"
      >
        Effects of microstructure in pin-loaded hole contact with clearance
      </a>
    </div>

    <div class="ccm-publication-authors">
      E. Radi and M. A. Güler
    </div>

    <div class="ccm-publication-journal">
      International Journal of Engineering Science, 221, 104454, 2026
    </div>

  </div>

  <div class="ccm-publication">

    <div class="ccm-publication-title">
      <a
        href="https://doi.org/10.1016/j.ijmecsci.2016.11.004"
        target="_blank"
        rel="noopener noreferrer"
      >
        On the analytical and finite element solution of plane contact problem of a rigid cylindrical punch sliding over a functionally graded orthotropic medium
      </a>
    </div>

    <div class="ccm-publication-authors">
      M. A. Güler, A. Küçüksucu, K. B. Yılmaz, and B. Yıldırım
    </div>

    <div class="ccm-publication-journal">
      International Journal of Mechanical Sciences, 120, 12–29, 2017
    </div>

  </div>

  <div class="ccm-publication">

    <div class="ccm-publication-title">
      <a
        href="https://doi.org/10.1016/j.ijsolstr.2011.12.005"
        target="_blank"
        rel="noopener noreferrer"
      >
        Tractive rolling contact mechanics of graded coatings
      </a>
    </div>

    <div class="ccm-publication-authors">
      M. A. Güler, S. Adibnazari, and Y. Alinia
    </div>

    <div class="ccm-publication-journal">
      International Journal of Solids and Structures, 49(6), 929–945, 2012
    </div>

  </div>

  <div class="ccm-publication">

    <div class="ccm-publication-title">
      <a
        href="https://doi.org/10.1016/j.mechmat.2005.11.006"
        target="_blank"
        rel="noopener noreferrer"
      >
        Contact mechanics of two deformable elastic solids with graded coatings
      </a>
    </div>

    <div class="ccm-publication-authors">
      M. A. Güler and F. Erdogan
    </div>

    <div class="ccm-publication-journal">
      Mechanics of Materials, 38(7), 633–647, 2006
    </div>

  </div>

  <div class="ccm-publication">

    <div class="ccm-publication-title">
      <a
        href="https://doi.org/10.1016/j.ijsolstr.2004.02.025"
        target="_blank"
        rel="noopener noreferrer"
      >
        Contact mechanics of graded coatings
      </a>
    </div>

    <div class="ccm-publication-authors">
      M. A. Güler and F. Erdogan
    </div>

    <div class="ccm-publication-journal">
      International Journal of Solids and Structures, 41(14), 3865–3889, 2004
    </div>

  </div>

</div>

<!-- ========================================================= -->
<!--                     COLLABORATIONS                       -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Collaborations</h2>

  <p>
    This research has been carried out through collaborations with researchers specializing in contact mechanics, generalized continuum theories, elasticity, tribology, advanced materials, and computational mechanics. These collaborations have supported the development of analytical benchmark solutions, finite element verification strategies, and new formulations for microstructured and layered media.
  </p>

</div>

<!-- ========================================================= -->
<!--                     FUTURE DIRECTIONS                    -->
<!-- ========================================================= -->

<div class="ccm-section">

  <h2>Future Directions</h2>

  <p>
    Future research will extend these formulations toward friction, wear, surface elasticity, multiphysics interactions, and data-assisted computational contact mechanics. Particular emphasis will be placed on micro-scale joints, curved interfaces, layered and coated systems, and reduced-order methods for rapid engineering prediction.
  </p>

</div>

<!-- ========================================================= -->
<!--                     BACK BUTTON                         -->
<!-- ========================================================= -->

<a class="ccm-back-button" href="/research/">
  ← Back to Research
</a>

</div>

---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-intro" style="margin-bottom:1.6rem;">

<div class="home-title" style="font-size:1.35rem;font-weight:700;margin-bottom:0.25rem;">
Professor of Mechanical Engineering
</div>

<div class="home-affiliation" style="font-size:1.05rem;font-weight:600;color:#555;margin-bottom:0.55rem;">
American University of the Middle East (AUM)
</div>

<div class="home-expertise" style="font-size:1rem;font-style:italic;color:#666;">
Computational Mechanics • Structural FEA (ANSYS, LS-DYNA, Abaqus) • Nonlinear Analysis • Fatigue &amp; Fracture Mechanics • Thermal-Structural Analysis • Crashworthiness
</div>

</div>

<hr style="margin:1.5rem 0 2rem 0;">

<style>
.home-button-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
  max-width: 900px;
}

.home-button {
  min-height: 54px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0.55rem 1rem;
  border: 1px solid #d2d2d2;
  border-radius: 999px;
  background: #ffffff;
  color: #2c7fa8 !important;
  font-size: 1rem;
  font-weight: 600;
  line-height: 1.2;
  text-align: center;
  text-decoration: none !important;
  box-sizing: border-box;
  transition:
    background-color 0.2s ease,
    color 0.2s ease,
    border-color 0.2s ease,
    transform 0.2s ease;
}

.home-button:hover,
.home-button:focus-visible {
  background: #2c7fa8;
  color: #ffffff !important;
  border-color: #2c7fa8;
  transform: translateY(-1px);
}

@media screen and (max-width: 800px) {
  .home-button-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 14px;
  }
}

@media screen and (max-width: 520px) {
  .home-title {
    font-size: 1.1rem !important;
    line-height: 1.25 !important;
  }

  .home-affiliation {
    font-size: 0.92rem !important;
    line-height: 1.3 !important;
  }

  .home-expertise {
    font-size: 0.88rem !important;
    line-height: 1.45 !important;
  }

  .page__content hr {
    margin: 1.1rem 0 1.35rem 0 !important;
  }

  .home-button {
    width: 100%;
    min-height: 46px;
    padding: 0.6rem 0.85rem;
    font-size: 0.96rem;
  }
}
</style>

<div class="home-button-grid">

<a class="home-button" href="/industrial-resume/">
Industrial Résumé
</a>

<a class="home-button" href="/projects/">
Engineering Projects
</a>

<a class="home-button" href="/cv/">
Academic CV
</a>

<a class="home-button" href="/research/">
Research
</a>

<a class="home-button" href="/publications/">
Publications
</a>

<a class="home-button" href="/teaching/">
Teaching &amp; Mentoring
</a>

</div>

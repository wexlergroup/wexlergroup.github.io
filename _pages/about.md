---
permalink: /about/
title: "About"
author_profile: false
layout: splash
about_page: true
excerpt: "Computational materials chemistry for energy and environmental applications at Washington University in St. Louis."
header:
  overlay_image: /assets/images/group-photo.jpg
  overlay_filter: "rgba(35, 22, 24, 0.72)"
feature_row:
  - image_path: /assets/images/catalyst-surfaces.png
    alt: "Surface phase diagram with ordered, disordered, and gas-phase adsorbates"
    title: "Surface Phase Diagrams"
    excerpt: "First-principles calculations and nested sampling predict catalyst surface structures as functions of temperature and pressure."
    url: "/research/#surface-phase-diagrams"
    btn_label: "Explore Surface Research"
    btn_class: "btn--primary"
  - image_path: /assets/images/hydrogen-production.png
    alt: "Solar thermochemical hydrogen-production cycle for a redox-active perovskite"
    title: "Solar Hydrogen Production"
    excerpt: "We design redox-active perovskites for solar thermochemical water splitting."
    url: "/research/#solar-thermochemical-hydrogen-production"
    btn_label: "Explore Hydrogen Research"
    btn_class: "btn--primary"
  - image_path: /assets/images/nanocrystals.png
    alt: "Halide-dependent synthesis pathways to wurtzite and rock-salt manganese sulfide nanocrystals"
    title: "Nanocrystal Synthesis"
    excerpt: "We study how precursors affect the crystal structure and phase of chalcogenide nanocrystals during synthesis."
    url: "/research/#nanocrystal-synthesis"
    btn_label: "Explore Nanocrystal Research"
    btn_class: "btn--primary"
---

<div class="about-content" markdown="1">

We develop computational methods to understand and design materials for hydrogen production,
CO<sub>2</sub> conversion, and solar energy conversion. Led by **Robert B. Wexler**, our group
is based in the Department of Chemistry at Washington University in St. Louis.
{: .about-intro}

## Research Areas

<div class="about-research">
{% for area in page.feature_row %}
  <article class="about-research-item">
    <img src="{{ area.image_path | relative_url }}" alt="{{ area.alt | escape }}" loading="lazy">
    <h3>{{ area.title }}</h3>
    <p>{{ area.excerpt }}</p>
    <a class="btn btn--primary" href="{{ area.url | relative_url }}">{{ area.btn_label }}</a>
  </article>
{% endfor %}
</div>

## Selected Papers and Preprints

<div class="about-publications">
  <div class="about-publication">
    <h3>Surface Phase Diagrams from Nested Sampling</h3>
    <p class="card-meta"><em>Phys. Chem. Chem. Phys.</em> · 2024</p>
    <p>First-principles calculations and nested sampling predict catalyst surface structures as functions of temperature and gas pressure.</p>
    <div class="about-links">
      <a href="https://doi.org/10.1039/D4CP00050A" aria-label="Read paper: Surface Phase Diagrams from Nested Sampling">Read paper</a>
    </div>
  </div>
  <div class="about-publication">
    <h3>Large-Scale Experimental Validation of Thermochemical Water-Splitting Oxides Discovered by Defect Graph Neural Networks</h3>
    <p class="card-meta"><em>Mater. Horiz.</em> · 2026</p>
    <p>Defect graph neural networks identified candidate thermochemical water-splitting oxides for experimental validation.</p>
    <div class="about-links">
      <a href="https://doi.org/10.1039/D5MH01566A" aria-label="Read paper: Large-Scale Experimental Validation of Thermochemical Water-Splitting Oxides">Read paper</a>
    </div>
  </div>
  <div class="about-publication">
    <h3>Equilibrium Thermochemistry and Crystallographic Morphology of Manganese Sulfide Nanocrystals</h3>
    <p class="card-meta"><em>arXiv</em> · 2026 · Preprint</p>
    <p>Equilibrium thermochemistry predicts the crystal phase and morphology of manganese sulfide nanocrystals.</p>
    <div class="about-links">
      <a href="https://doi.org/10.48550/arXiv.2603.05420" aria-label="Read preprint: Equilibrium Thermochemistry and Crystallographic Morphology of Manganese Sulfide Nanocrystals">Read preprint</a>
    </div>
  </div>
</div>

## Principal Investigator

<div class="about-pi">
  <img src="/assets/images/rob-photo-1.jpg" alt="Robert B. Wexler" class="about-portrait">
  <div class="about-pi-text">
  <h3>Robert B. Wexler</h3>
  <p class="card-meta">Assistant Professor of Chemistry, Washington University in St. Louis</p>
  <p>Rob develops first-principles, Monte Carlo, and machine-learning methods for materials and interfaces. Before joining WashU, he was a postdoctoral researcher at Princeton University (2019–2022). He received his Ph.D. from the University of Pennsylvania in 2019.</p>
  <div class="about-links">
    <a href="/people/">Group Members</a>
    <a href="https://scholar.google.com/citations?user=sCqcoMsAAAAJ&hl=en&oi=ao">Google Scholar</a>
    <a href="mailto:wexler@wustl.edu">Email</a>
  </div>
  </div>
</div>

## Join the Group

<div class="about-recruitment">
  <p>The Wexler Group is recruiting Ph.D. students for all ongoing research projects. Prospective graduate students apply through the Washington University Department of Chemistry. WashU undergraduates and prospective postdoctoral researchers may inquire by email.</p>
  <div class="about-links">
    <a href="https://chemistry.wustl.edu/graduate">Graduate Program</a>
    <a href="mailto:wexler@wustl.edu">Email Prof. Wexler</a>
  </div>
</div>

## Explore Our Work

[Methods and Software](/software/){: .btn .btn--inverse}
[Research](/research/){: .btn .btn--inverse}
[Papers](/papers/){: .btn .btn--inverse}

</div>

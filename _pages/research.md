---
permalink: /research/
title: "Research"
author_profile: false
layout: splash
research_page: true
---

<div class="research-page" markdown="1">

# Research

The Wexler Group develops computational materials chemistry methods for energy conversion and environmental
applications. The projects described here concern catalyst surface reconstruction, solar thermochemical hydrogen
production, and nanocrystal synthesis. Related work on CO<sub>2</sub> conversion, ferroelectric energy harvesting, and
solar energy conversion is included on the [Papers](/papers/) page.


Across these projects, we use statistical thermodynamics, first-principles quantum-mechanical calculations, Monte Carlo
simulations, data science, and machine learning in collaboration with experimental groups. We use these methods to connect
atomic-scale structures and energetics to thermodynamic observables and materials behavior during synthesis or under
operating conditions. The current research questions are:


* How can catalyst surface structures be predicted as functions of temperature and chemical environment?
* How does perovskite composition affect redox thermodynamics and stability during solar thermochemical water splitting?
* How do precursors and ligands affect the crystal structure and phase of chalcogenide nanocrystals during synthesis?

<nav class="research-nav" aria-label="Research topics">
  <a href="#surface-phase-diagrams">Surface Phase Diagrams</a>
  <a href="#solar-thermochemical-hydrogen-production">Solar Hydrogen Production</a>
  <a href="#nanocrystal-synthesis">Nanocrystal Synthesis</a>
  <a href="#computing-resources">Computing Resources</a>
</nav>

## Surface Phase Diagrams

<div class="research-topic">
  <figure class="research-figure"><img src="/assets/images/catalyst-surfaces.png" alt="Surface phase diagram with ordered, disordered, and gas-phase adsorbates" loading="lazy"></figure>
  <div class="research-description">
    <p>Catalyst activity and selectivity depend on surface structure and composition under reaction conditions.
    Temperature, pressure, and chemical environment can drive surface reconstruction and degradation, while
    measurements under reactive conditions remain challenging. We develop computational methods to predict
    equilibrium catalyst surface structures and use them as reference states for studying catalytic turnover.</p>
    <p>Our initial demonstration applied nested sampling to Lennard-Jones gas particles adsorbed on flat and
    stepped Lennard-Jones surfaces. From the sampled energies, we constructed a canonical partition function
    and calculated heat capacities and structural order parameters to identify adsorbate phases and transitions.</p>
  </div>
</div>

<div class="research-references" markdown="1">

### Related Work

- <a class="person-link" href="{{ '/people/#ray-m-yang' | relative_url }}" aria-label="Ray M. Yang">Yang, M.</a>; Pártay, L. B.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a> Surface Phase Diagrams from Nested Sampling. *Phys. Chem. Chem. Phys.* **2024**,
  *26* (18), 13862–13874.
  [PDF](../assets/papers/Yang2024p13862.pdf){: aria-label="PDF: Surface phase diagrams from nested sampling"} | [DOI](https://doi.org/10.1039/D4CP00050A){: aria-label="DOI: Surface phase diagrams from nested sampling"}
- <a class="person-link" href="{{ '/people/#ray-m-yang' | relative_url }}" aria-label="Ray M. Yang">Yang, R.</a>; <a class="person-link" href="{{ '/people/#junchi-chen' | relative_url }}" aria-label="Junchi Chen">Chen, J.</a>; <a class="person-link" href="{{ '/people/#douglas-thibodeaux' | relative_url }}" aria-label="Douglas Thibodeaux">Thibodeaux, D.</a>; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a> FreeBird.jl: An Extensible Toolbox for Simulating Interfacial Phase
  Equilibria. *J. Chem. Theory Comput.* **2025**, *21* (21), 10765–10779.
  [PDF](../assets/papers/Yang2025p10765.pdf){: aria-label="PDF: FreeBird.jl"} | [DOI](https://doi.org/10.1021/acs.jctc.5c01348){: aria-label="DOI: FreeBird.jl"}
- Chatbipho, T.; <a class="person-link" href="{{ '/people/#ray-m-yang' | relative_url }}" aria-label="Ray M. Yang">Yang, R.</a>; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a>; Pártay, L. B. Adsorbate Phase Transitions on Nanoclusters from Nested Sampling.
  *J. Chem. Phys.* **2025**, *163* (17), 174701.
  [PDF](../assets/papers/Chatbipho2025p174701.pdf){: aria-label="PDF: Adsorbate phase transitions on nanoclusters"} | [DOI](https://doi.org/10.1063/5.0283538){: aria-label="DOI: Adsorbate phase transitions on nanoclusters"}

</div>

## Solar Thermochemical Hydrogen Production

<div class="research-topic">
  <figure class="research-figure"><img src="/assets/images/hydrogen-production.png" alt="Solar thermochemical hydrogen-production cycle and perovskite redox process" loading="lazy"></figure>
  <div class="research-description">
    <p>Two-step solar thermochemical hydrogen production cycles use redox-active metal oxides to split water.
    Concentrated solar heat removes oxygen from the oxide at high temperature and low oxygen partial pressure.
    Steam then restores the oxygen and releases hydrogen. We study how perovskite composition and oxygen-vacancy
    thermodynamics affect this cycle's kinetics, stability, and durability.</p>
    <p>Experiments on our (Ca, Ce)(Ti, Mn)O<sub>3−δ</sub> perovskite showed reversible oxygen-vacancy formation
    and filling without a reported bulk phase transition under the conditions studied. Building on HydroGEN results,
    we combine modeling, synthesis, characterization, and thermodynamic measurements with reactor design,
    system analysis, and techno-economic analysis to evaluate performance, cost, and scalability.</p>
  </div>
</div>

<div class="research-references" markdown="1">

### Related Work

- Choudhary, K.; Wines, D.; Li, K.; Garrity, K. F.; Gupta, V.; Romero, A. H.; Krogel, J. T.; Saritas, K.; Fuhr, A.;
  Ganesh, P.; Kent, P. R. C.; Yan, K.; Lin, Y.; Ji, S.; Blaiszik, B.; Reiser, P.; Friederich, P.; Agrawal, A.; Tiwary, P.;
  Beyerle, E.; Minch, P.; Rhone, T. D.; Takeuchi, I.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a>; Mannodi-Kanakkithodi, A.; Ertekin, E.; Mishra, A.;
  Mathew, N.; Wood, M.; Rohskopf, A. D.; Hattrick-Simpers, J.; Wang, S.-H.; Achenie, L. E. K.; Xin, H.; Williams, M.;
  Biacchi, A. J.; Tavazza, F. JARVIS-Leaderboard: A Large-Scale Benchmark of Materials Design Methods.
  *npj Comput. Mater.* **2024**, *10*, 93.
  [PDF](../assets/papers/Choudhary2024p93.pdf){: aria-label="PDF: JARVIS-Leaderboard"} | [DOI](https://doi.org/10.1038/s41524-024-01259-w){: aria-label="DOI: JARVIS-Leaderboard"}
- Way, L.; Spataru, C. D.; Jones, R. E.; Trinkle, D. R.; Rowberg, A. J. E.; Varley, J. B.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a>; Smyth, C. M.;
  Douglas, T. C.; Bishop, S. R.; Fuller, E. J.; McDaniel, A. H.; Lany, S.; Witman, M. D. Defect Diffusion Graph Neural
  Networks for Materials Discovery in High-Temperature Energy Applications. *Chem. Mater.* **2025**, *37* (17), 6473–6484.
  [PDF](../assets/papers/Way2025p6473.pdf){: aria-label="PDF: Defect diffusion graph neural networks"} | [DOI](https://doi.org/10.1021/acs.chemmater.5c00021){: aria-label="DOI: Defect diffusion graph neural networks"}
- Douglas, T. C.; Dzara, M. J.; Rowberg, A. J. E.; King, K. A.; Syrigou, M.; Strange, N. A.; Bell, R. T.; Goyal, A.;
  Guan, P.-W.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a>; Varley, J. B.; Ogitsu, T.; Lany, S.; McDaniel, A. H.; Bishop, S. R.; Witman, M. D. Large-Scale
  Experimental Validation of Thermochemical Water-Splitting Oxides Discovered by Defect Graph Neural Networks.
  *Mater. Horiz.* **2026**, *13* (2), 829–839.
  [PDF](../assets/papers/Douglas2026p829.pdf){: aria-label="PDF: Experimental validation of water-splitting oxides"} | [DOI](https://doi.org/10.1039/D5MH01566A){: aria-label="DOI: Experimental validation of water-splitting oxides"}
- Witman, M. D.; <a class="person-link" href="{{ '/people/#sebastian-pujet' | relative_url }}" aria-label="Sebastian Pujet">Pujet, S.</a>; Rowberg, A. J. E.; Sutton, C.; Varley, J. B.; Lany, S.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a> Transfer Learning on
  Universal Interatomic Potential Embeddings Improves Generalization in Structure-Property Defect Models. *ChemRxiv*
  **2026**. Preprint, version 1.
  [PDF](../assets/papers/Witman2026.pdf){: aria-label="PDF: Transfer learning for defect models"} | [DOI](https://doi.org/10.26434/chemrxiv.15003938/v1){: aria-label="DOI: Transfer learning for defect models"}
- <a class="person-link" href="{{ '/people/#manish-kumar' | relative_url }}" aria-label="Manish Kumar">Kumar, M.</a>; Ali, N.; Witman, M. D.; Zhai, S.; Miller, J. E.; Ermanoski, I.; Stechel, E. B.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a> Local B-Site
  Chemistry Controls Oxygen-Vacancy Energetics in Ca–Ce–Ti–Mn Perovskites for Thermochemical Hydrogen Production.
  *arXiv* **2026**, arXiv:2607.28752. Preprint.
  [PDF](https://arxiv.org/pdf/2607.28752){: aria-label="PDF: Local B-site chemistry and oxygen vacancies"} | [DOI](https://doi.org/10.48550/arXiv.2607.28752){: aria-label="DOI: Local B-site chemistry and oxygen vacancies"}

</div>

## Nanocrystal Synthesis

<div class="research-topic">
  <figure class="research-figure"><img src="/assets/images/nanocrystals.png" alt="Halide-dependent synthesis pathways to wurtzite and rock-salt manganese sulfide nanocrystals" loading="lazy"></figure>
  <div class="research-description" markdown="1">

We combine experimental and computational methods to determine how halides affect the crystal structure and phase of
manganese chalcogenide nanocrystals during synthesis. We identify prenucleation species, measure the
thermochemistry of reactions and surface-ligand interactions, and monitor nucleation and growth kinetics using in situ
techniques. We use first-principles calculations to characterize atomic-scale interactions and mechanisms that affect
crystal structure and phase. We use these results as inputs for kinetic and thermodynamic models of nanocrystal nucleation and
growth. We also examine lanthanide chalcogenide nanocrystals, which have been studied less extensively than
manganese chalcogenide nanocrystals. We seek chemical principles for synthesizing Mn and Ln chalcogenide nanocrystals and
test whether those principles apply to other material classes.

  </div>
</div>

<div class="research-references" markdown="1">

### Related Work

- <a class="person-link" href="{{ '/people/#junchi-chen' | relative_url }}" aria-label="Junchi Chen">Chen, J.</a>; Subramani, T.; Mekan, D.; Gendler, D.; <a class="person-link" href="{{ '/people/#ray-m-yang' | relative_url }}" aria-label="Ray M. Yang">Yang, R.</a>; <a class="person-link" href="{{ '/people/#manish-kumar' | relative_url }}" aria-label="Manish Kumar">Kumar, M.</a>; Householder, M.; Rosado Ortiz, A.;
  Hernandez-Pagan, E. A.; Lilova, K.; <a class="person-link" href="{{ '/people/#robert-b-wexler' | relative_url }}" aria-label="Robert B. Wexler">Wexler, R. B.</a> Equilibrium Thermochemistry and Crystallographic Morphology of
  Manganese Sulfide Nanocrystals. *arXiv* **2026**, arXiv:2603.05420. Preprint.
  [PDF](../assets/papers/Chen2026.pdf){: aria-label="PDF: Manganese sulfide nanocrystals"} | [DOI](https://doi.org/10.48550/arXiv.2603.05420){: aria-label="DOI: Manganese sulfide nanocrystals"}

</div>

## Computing Resources

Our group uses its bear, dragon, and wapiti systems for computational research.
Expand each entry for hardware details.

<div class="research-computing">
  <details>
    <summary>bear — Wexler Group</summary>
    <ul>
      <li>Dell PowerEdge T550</li>
      <li>Intel Xeon Gold 6338 processors, 2.00 GHz</li>
      <li>64 cores</li>
    </ul>
  </details>
  <details>
    <summary>dragon — Wexler Group</summary>
    <ul>
      <li>Dell PowerEdge C6520</li>
      <li>Intel Xeon Gold 6338 processors, 2.00 GHz</li>
      <li>256 cores across four nodes</li>
    </ul>
  </details>
  <details>
    <summary>wapiti — Wexler Group</summary>
    <p>A group-owned, single-node counterpart to dragon.</p>
  </details>
  <details>
    <summary>Theta — Past Computing Resource</summary>
    <p>Our group previously used Theta at the Argonne Leadership Computing Facility.
    <a href="https://ar23.alcf.anl.gov/features/theta">Theta retired at the end of 2023</a>.</p>
    <ul>
      <li>Intel-Cray XC40; 11.7 petaflops</li>
      <li>4,392 nodes and 281,088 cores</li>
      <li>Intel Xeon Phi 7230 processors</li>
    </ul>
  </details>
</div>

</div>

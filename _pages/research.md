---
permalink: /research/
title: "Research"
author_profile: false
layout: splash
feature_row2:
  - image_path: /assets/images/theta.jpg
    alt: "Theta supercomputer at Argonne National Laboratory"
    title: "Argonne Leadership Computing Facility"
    excerpt: "**Theta** <br>
    *Architecture* = Intel-Cray XC40 <br>
    *Speed* = 11.7 petaflops <br>
    *Processor per Node* = one 64-core, 1.3-GHz Intel Xeon Phi 7230 <br>
    *Nodes* = 4,392 <br> 
    *Cores* = 281,088 <br> 
    *Memory* = 843 TB <br> 
    *High-Bandwidth Memory* = 70 TB <br>
    *Interconnect* = Aries network with Dragonfly topology"
---

<br>

# Table of Contents

1. [Research](#research)
2. [Surface Phase Diagrams](#surface-phase-diagrams)
3. [Solar Thermochemical Hydrogen Production](#solar-thermochemical-hydrogen-production)
4. [Nanocrystal Synthesis](#nanocrystal-synthesis)
5. [Computing Resources](#computing-resources)

<br>

# Research

The Wexler Group develops computational materials chemistry methods for energy conversion and environmental
applications. The projects described here concern catalyst surface reconstruction, solar thermochemical hydrogen
production, and nanocrystal synthesis. Related work on CO<sub>2</sub> conversion, ferroelectric energy harvesting, and
solar energy conversion is included on the [Papers](/papers/) page.
{: .text-justify}

Across these projects, we use statistical thermodynamics, first-principles quantum-mechanical calculations, Monte Carlo
simulations, data science, and machine learning in collaboration with experimental groups. We use these methods to connect
atomic-scale structures and energetics to thermodynamic observables and materials behavior during synthesis or under
operating conditions. The current research questions are:
{: .text-justify}

* How can catalyst surface structures be predicted as functions of temperature and chemical environment?
* How does perovskite composition affect redox thermodynamics and stability during solar thermochemical water splitting?
* How do precursors and ligands affect the crystal structure and phase of chalcogenide nanocrystals during synthesis?

## Surface Phase Diagrams

<div style="text-align: justify;">
    <img src="/assets/images/catalyst-surfaces.png" alt="Surface phase diagram with ordered, disordered, and gas-phase adsorbates" style="width:50%; float:right; margin-left:20px;">
    <p>Industrial chemical processes use heterogeneous catalysts. Their activity and selectivity depend on
    the atomic structure and composition of exposed surfaces under reaction conditions. Surface reconstruction changes
    surface periodicity, species coordination, composition, or thickness relative to the bulk material. Degradation
    decreases catalytic activity or selectivity over time under chemical or operational stresses. Temperature, pressure,
    and chemical composition affect both processes. Measurements under reactive conditions can be complicated by
    interactions with solutes and solvents, oxidation during sample transfer, and conditions that can damage experimental
    apparatus. We develop computational methods to predict equilibrium reconstructions of catalyst surfaces as functions of
    temperature and chemical environment. We use these equilibrium structures as reference states in subsequent studies of
    surfaces during catalytic turnover. As an initial demonstration, we applied nested sampling to Lennard-Jones gas
    particles adsorbed on low-index and vicinal Lennard-Jones solid surfaces. We used the sampled energies to construct a
    canonical partition function and calculate ensemble averages, including the constant-volume heat capacity and order
    parameters that characterize adsorbate phases.</p>
</div>

Yang, M.; Pártay, L. B.; Wexler, R. B. Surface Phase Diagrams from Nested Sampling. *Phys. Chem. Chem. Phys.* **2024**,
*26* (18), 13862.
{: .text-justify}
Chatbipho, T.; Yang, R.; Wexler, R. B.; Pártay, Livia B.
Adsorbate Phase Transitions on Nanoclusters from Nested Sampling.
*arXiv* **2025**, 2506.01295.
{: .text-justify}

## Solar Thermochemical Hydrogen Production

<div style="text-align: justify;">
    <img src="/assets/images/hydrogen-production.png" alt="Solar thermochemical hydrogen-production cycle and perovskite redox process" style="width:50%; float:right; margin-left:20px;">
    <p>Two-step solar thermochemical hydrogen production (STCH) cycles use redox-active metal oxides (MOx) to split water
    and produce hydrogen. During thermal reduction, concentrated solar radiation heats MOx above 1500 K at low oxygen
    partial pressure, producing the oxygen-deficient state MOx–δ. During reoxidation, superheated steam restores the
    initial oxide composition and produces hydrogen. Experiments on our (Ca, Ce)(Ti, Mn)O3–δ perovskite showed
    oxygen-vacancy formation and filling during cycling without a reported bulk phase transition under the conditions
    studied. We evaluate how composition
    and vacancy thermodynamics affect reaction kinetics, cycling stability, and durability. The project includes
    theoretical modeling, synthesis, characterization, material thermodynamics, reactor design and prototyping, system
    mass and energy flow analysis, and techno-economic analysis. Using prior HydroGEN results, we are developing an STCH
    cycle based on (Ca, Ce)(Ti, Mn)O3–δ perovskites and evaluating material cost, stability, and scalability.</p>
</div>

Wexler, R. B.; Sai Gautam, G.; Bell, R. T.; Shulda, S.; Strange, N. A.; Trindell, J. A.; Sugar, J. D.; Nygren, E.;
Sainio, S.; McDaniel, A. H.; Ginley, D.; Carter, E. A.; Stechel, E. B. Multiple and Nonlocal Cation Redox in Ca–Ce–Ti–Mn
Oxide Perovskites for Solar Thermochemical Applications. *Energy Environ. Sci.* **2023**, *16* (6), 2550.
{: .text-justify}
Way, L.; Spataru, C. D.; Jones, R.; Trinkle, D. R.; Rowberg, A. J. E.; Varley, J. B.; Wexler, R. B.; Smyth, C. M.; Douglas, T. C.; Bishop, S. R.; Fuller, E.; McDaniel, A. H.; Lany, S.; Witman, M. D.
Defect Diffusion Graph Neural Networks for Materials Discovery in High-Temperature, Clean Energy Applications.
*ChemRxiv* **2024**.
{: .text-justify}

## Nanocrystal Synthesis

We combine experimental and computational methods to determine how halides affect the crystal structure and phase of
manganese chalcogenide nanocrystals during synthesis. We identify prenucleation species, measure the
thermochemistry of reactions and surface-ligand interactions, and monitor nucleation and growth kinetics using in situ
techniques. We use first-principles calculations to characterize atomic-scale interactions and mechanisms that affect
crystal structure and phase. We use these results as inputs for kinetic and thermodynamic models of nanocrystal nucleation and
growth. We also examine lanthanide chalcogenide nanocrystals, which have been studied less extensively than
manganese chalcogenide nanocrystals. We seek chemical principles for synthesizing Mn and Ln chalcogenide nanocrystals and
test whether those principles apply to other material classes.
{: .text-justify}

## Computing Resources

<link rel="stylesheet" type="text/css" href="../styles.css">
<script src="../script.js" defer></script>

<div class="card" onclick="toggleCard(this)">
  <div class="container">
    <p><b>bear</b></p>
    <p><i>Wexler Group</i></p>
    <div class="hidden-content">
      <p>PowerEdge T550</p>
      <p>Intel Xeon Gold 6338 Processor</p>
      <p>2.00 GHz</p>
      <p>64 cores</p>
    </div>
  </div>
</div>

<div class="card" onclick="toggleCard(this)">
  <div class="container">
    <p><b>dragon</b></p>
    <p><i>Wexler Group</i></p>
    <div class="hidden-content">
      <p>Current Configuration: PowerEdge C6520</p>
      <p>Intel Xeon Gold 6338 Processor</p>
      <p>2.00 GHz</p>
      <p>256 cores (4 nodes)</p>
    </div>
  </div>
</div>

<div class="card" onclick="toggleCard(this)">
  <div class="container">
    <p><b>Theta</b></p>
    <p><i>Argonne Leadership Computing Facility</i></p>
    <div class="hidden-content">
      <p>Intel-Cray XC40</p>
      <p>11.7 petaflops</p>
      <p>One 64-core, 1.3-GHz Intel Xeon Phi 7230 processor per node</p>
      <p>4,392 nodes and 281,088 cores</p>
      <p>843 TB memory and 70 TB high-bandwidth memory</p>
      <p>Aries network with Dragonfly topology</p>
    </div>
  </div>
</div>

---
permalink: /research/
title: "Research"
author_profile: false
layout: splash
feature_row2:
  - image_path: /assets/images/theta.jpg
    alt: "Argonne Leadership Computing Facility"
    title: "Argonne Leadership Computing Facility"
    excerpt: "**Theta** <br>
    *Architecture* = Intel-Cray XC40 <br>
    *Speed* = 11.7 petaflops <br>
    *Processor per node* = 64-core, 1.3-GHz Intel Xeon Phi 7230 <br>
    *Nodes* = 4,392 <br> 
    *Cores* = 281,088 <br> 
    *Memory* = 843 TB <br> 
    *High-bandwidth memory* = 70 TB <br>
    *Interconnect* = Aries network with Dragonfly topology"
---

<br>

# Table of Contents

1. [Wexler Group Research](#wexler-group-research)
2. [Surface Phase Diagrams](#surface-phase-diagrams)
3. [Solar Thermochemical Hydrogen Production](#solar-thermochemical-hydrogen-production)
4. [Nanocrystal Synthesis](#nanocrystal-synthesis)
5. [Computing Resources](#computing-resources)

<br>

# Wexler Group Research

As the damages associated with climate change intensify in the coming years, it will become increasingly important for
educators and researchers to focus on sustainable energy and environmental remediation. Computational materials
chemistry has the potential to revolutionize the industries responsible for these damages by alleviating their reliance
on fossil fuels, precious metals, and toxic elements. Inspired by this potential, the Wexler group's research centers
around solving grand challenges in energy and environment by designing and developing next-generation technologies for
water splitting, CO<sub>2</sub> utilization, solar energy conversion, and environmental energy harvesting. More
specifically, we aim, through theoretical innovations and experimental collaborations, to answer questions like
{: .text-justify}

* "Can we design materials for hydrogen production that are active and stable in extreme environments?"
* "How do precursors influence crystal structure and composition during the synthesis of nanocrystals?"
* "Which properties govern the performance of ferroelectric energy harvesters for the Internet of Things?"
* "How can we overcome selectivity-conversion limits for the electrochemical CO<sub>2</sub> reduction reaction?"
* "What factors limit solar-cell efficiency, and how can we control them?"

Answering these questions in catalysis, solar power, and transduction will require improvements in the way that
materials interfaces are currently modeled, which can be achieved via next-generation computational methods for
statistical thermodynamics that combine my expertise in first-principles quantum mechanics calculations, Monte Carlo
simulations, data science, and machine learning. More broadly, the Wexler group's research can be subdivided into four
distinct visions that address these challenges from different angles:
{: .text-justify}

1. To develop state-of-the-art computational techniques for the realistic modeling of materials interfaces
2. To provide fundamental understanding and design principles for sustainable H<sub>2</sub> production and controllable
   CO<sub>2</sub> conversion
3. To create efficient interatomic potentials for the accurate simulation and rational design of ferroelectric energy
   harvesters
4. To improve solar-cell efficiency via chemical modification and interfacial engineering

## Surface Phase Diagrams

<div style="text-align: justify;">
    <img src="/assets/images/catalyst-surfaces.png" alt="" style="width:50%; float:right; margin-left:20px;">
    <p>Heterogeneous catalysts are essential for industrial chemical production. Enhancing their efficiency requires an
    atomic-level understanding of surface structures and active sites. Key factors in catalyst design include surface
    reconstruction and degradation. Surface reconstruction involves changes in periodicity, species coordination,
    composition, and thickness along the surface normal, differing from the bulk material. Degradation refers to the gradual
    loss of catalytic activity and selectivity over time due to environmental or operational stresses. The operating
    environment significantly impacts these transformations, affecting catalyst activity and selectivity. Designing
    efficient catalysts necessitates understanding the conditions under which surfaces restructure in situ. Surface
    structure and composition measurements are often complicated by interactions with solutes and solvents, ex-situ
    oxidation, and reactive conditions that can damage experimental apparatus. This project focuses on developing
    computational methodologies to predict the equilibrium reconstructions of catalyst surfaces. Although active catalysts
    are typically out of equilibrium, they can establish a surface equilibrium before catalysis begins. The primary goal is
    to identify the most stable catalyst surface form, providing a foundation for further studies on its behavior during
    active catalysis. As a proof-of-concept, we applied nested sampling to the adsorption of Lennard-Jones gas particles on
    low-index and vicinal Lennard-Jones solid surfaces. By constructing the canonical partition function from the recorded
    energies, we can calculate ensemble averages of thermodynamic properties, such as constant-volume heat capacity and
    order parameters that characterize adsorbate phase structures.</p>
</div>

Yang, M.; Pártay, L. B.; Wexler, R. B. Surface Phase Diagrams from Nested Sampling. *Phys. Chem. Chem. Phys.* **2024**,
*26* (18), 13862.
{: .text-justify}

## Solar Thermochemical Hydrogen Production

<div style="text-align: justify;">
    <img src="/assets/images/hydrogen-production.png" alt="Hydrogen Production" style="width:50%; float:right; margin-left:20px;">
    <p>Two-step solar thermochemical hydrogen production (STCH) cycles utilize redox-active metal oxides (MOx) that undergo thermal reduction and re-oxidation to split water and produce hydrogen. The STCH cycle involves heating MOx to temperatures exceeding 1500 K using concentrated solar radiation. The material reduces to an oxygen-deficient state (MOx–δ) at these high temperatures and low oxygen partial pressures. In the subsequent step, the reduced MOx is exposed to superheated steam, leading to re-oxidation and water splitting, generating hydrogen and regenerating the original MOx. Our perovskite material, (Ca, Ce)(Ti, Mn)O3–δ, exhibits remarkable off-stoichiometric redox activity, forming and filling oxygen vacancies during the thermal reduction and re-oxidation steps without significant bulk phase transitions, enhancing kinetics, cyclability, and durability. This interdisciplinary project integrates theoretical modeling, synthesis, characterization, material thermodynamics, reactor design and prototyping, system mass/energy flow analysis, and technoeconomic analysis. The goal is to develop a robust, cost-effective STCH cycle using (Ca, Ce)(Ti, Mn)O3–δ perovskites, leveraging their compositional flexibility and abundant metal precursors. Building on HydroGEN advances, this research addresses affordability, stability, and large-scale clean hydrogen production challenges.</p>
</div>

Wexler, R. B.; Sai Gautam, G.; Bell, R. T.; Shulda, S.; Strange, N. A.; Trindell, J. A.; Sugar, J. D.; Nygren, E.;
Sainio, S.; McDaniel, A. H.; Ginley, D.; Carter, E. A.; Stechel, E. B. Multiple and Nonlocal Cation Redox in Ca–Ce–Ti–Mn
Oxide Perovskites for Solar Thermochemical Applications. *Energy Environ. Sci.* **2023**, *16* (6), 2550.
{: .text-justify}

## Nanocrystal Synthesis

This research aims to develop a framework combining experimental and computational methods to understand how halides
influence the crystal structure and phase of manganese chalcogenide nanocrystals during synthesis. Key objectives
include identifying pre-nucleation species, conducting thermochemical measurements of reactions and surface-ligand
interactions, and monitoring nucleation and growth kinetics using in situ techniques. We use quantum-mechanics-based
calculations to reveal atomic-scale interactions and mechanisms determining crystal structures and phases. These
calculations inform kinetic and thermodynamic models of nanocrystal nucleation and growth, providing multi-scale
computational guidance for controlled synthesis. The research extends to lanthanide chalcogenide nanocrystals, which
have unique optical and magnetic properties but are less explored. The ultimate goal is to enhance the chemical
understanding of Mn and Ln chalcogenide nanocrystal synthesis, offering insights for the broader scientific community
and aiding in synthesizing other material classes.
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
      <p>PowerEdge C6520</p>
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
      <p></p>
    </div>
  </div>
</div>
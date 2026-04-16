# Glyxon-Zurvatronics ⚙️🧬
**Analytical Models of Subtractive Ontology and Informational Collapse in Molecular Motors**

[![ALIFE](https://img.shields.io/badge/ALIFE-2026-blue.svg)](https://alife.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Glyxon Biolabs](https://img.shields.io/badge/Lab-Glyxon_Biolabs-black.svg)]()

> *"Life does not compute to move; it computes to persist."*

This repository contains the computational simulations and analytical models (Wolfram Mathematica / Python) supporting the **Theory of Zurvatronics**, as presented in the ALIFE 2026 manuscript: *"Biomolecules as Thermodynamic Computers, Subtractive Ontology and the Informational Collapse"*.

---

<div align="center">
  <h2>⚡ Interactive Simulation</h2>
  <p>Observe the Catch-Bond disassembly and the Thermodynamic Wedge in real-time.</p>
  <a href="https://glyxon.github.io/Zurvatronics/interactive_sim/">
    <img src="https://img.shields.io/badge/-START_SIMULATION-121212?style=for-the-badge&logo=matrix&logoColor=2ECC71" alt="Start Simulation">
  </a>
  <p><i>Visualizing the phase transition and the Zurvān Gap directly in your browser.</i></p>
</div>

---

## 👁️ The Subtractive Agency Manifesto
Traditional bioenergetic models treat biological agency as an additive process: organisms accumulate complexity and consume free energy to build order. Zurvatronics proposes an inhibitory framework. Directionality (and thus, life) emerges from the **systematic subtraction of informational entropy**—the topological "pruning" of non-functional stochastic trajectories. 

The macroscopic work (rotation) is the byproduct of the system's continuous effort to avoid thermodynamic collapse.

## 🧮 Theoretical Core: The Zurvān Gap & The "Knee"
The code in this repository models the *Pseudomonas putida* MotAB stator as a noise-driven informational filter (a Hysteresis Latch). 

### The Thermodynamic Wedge
The stability of the motor is dictated by the "Thermodynamic Wedge"—the energy gap between the Catch-Bond anchoring strength and the ambient thermal noise ($k_B T$). As rotational speed increases, the wedge narrows. 

### Resolving the Torque-Speed "Knee"
For decades, biophysics has observed an abrupt "knee" in torque-speed curves. Zurvatronics identifies this knee not as a kinetic limitation of protons, but as the **Critical Threshold ($Z_c$)**. 
* **$Z > Z_c$**: The wedge is thick; 11 stators remain anchored (The Plateau).
* **$Z < Z_c$**: The wedge collapses; informational filtering fails, leading to an abrupt population-level disassembly (The Knee).

We term the temperature-dependent shift of this collapse the **Zurvān Gap**: a predictive window where thermal noise overrides the Catch-Bond at specific frequencies.

## 📂 Repository Architecture

* `/interactive_sim/`
  * `index.html`: Web-based JS simulator (The Motor Wheel & Dynamic Wedge).
* `/src/mathematica/`
  * `Zurvan_Phase_Diagram.nb`: Analytical calculation of Swineshead's *Latitudo* (Figure A).
  * `Population_Disassembly.nb`: Sigmoidal Catch-Bond transition (Figure B).
* `/src/python_ports/`
  * `zurvan_gap_sim.py`: NumPy implementation of the assembly equations.
* `/docs/`
  * `ALIFE2026_Preprint

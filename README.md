# Glyxon-Zurvatronics ⚙️🧬
**Analytical Models of Subtractive Ontology and Informational Collapse in Molecular Motors**

[![ALIFE](https://img.shields.io/badge/ALIFE-2026-blue.svg)](https://alife.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Glyxon Biolabs](https://img.shields.io/badge/Lab-Glyxon_Biolabs-black.svg)]()

> *"Life does not compute to move; it computes to persist."*

This repository contains the computational simulations and analytical models (Wolfram Mathematica / Python) supporting the **Theory of Zurvatronics**, as presented in the ALIFE 2026 manuscript: *"Biomolecules as Thermodynamic Computers, Subtractive Ontology and the Informational Collapse"*.

## 👁️ The Subtractive Agency Manifesto
Traditional bioenergetic models treat biological agency as an additive process: organisms accumulate structural complexity and consume free energy to maintain states far from thermodynamic equilibrium. Zurvatronics proposes an inhibitory framework. Directionality (and thus, life) emerges from the **systematic subtraction of informational entropy**; it is the topological "pruning" of non-functional stochastic trajectories from a system's conformational phase space. 

The macroscopic mechanical work we observe—e.g., the directed rotation of the bacterial flagellum—is not the primary teleological goal of the system, but the byproduct of its continuous effort to avoid thermodynamic collapse.

## 🧮 The Theoretical Hardware: The Zurvān Gap
The code in this repository models the *Pseudomonas putida* MotAB flagellar stator not as a mechanical gear, but as a noise-driven informational filter (a Hysteresis Latch). 

By resolving the Catch-Bond dynamics of Intrinsically Disordered Regions (IDRs) against thermal noise ($k_B T$), the scripts calculate the **Accumulated Action ($Z$)** using Richard Swineshead's *Latitudo formarum* (ca. 1350). 

**The Analytical Breakthrough:**
The model demonstrates that the classic "knee" (the abrupt loss of torque at high speeds) is not a kinetic failure of proton flux, but a geometric phase transition: the **Critical Limit ($Z_c$)**.
Upon crossing $Z_c$, the thickness of the system's "Thermodynamic Wedge" drops to zero. The simulations predict an abrupt, temperature-dependent population disassembly. We term this the **Zurvān Gap**: a predictive ~10 Hz operational window where a motor at 303 K collapses into thermal noise, while its counterpart at 277 K maintains its informational integrity.

## 📂 Repository Architecture

* `/src/mathematica/`
  * `Zurvan_Phase_Diagram.nb`: Analytical calculation of Swineshead's *Latitudo* and generation of the $Z$ vs $\omega$ Phase Diagram (Figure A).
  * `Population_Disassembly.nb`: Sigmoidal Catch-Bond transition and stator population disassembly (Figure B).
* `/src/python_ports/`
  * `zurvan_gap_sim.py`: Vectorized Python port (NumPy/SciPy) of the assembly equations for integration with complex systems simulations.
* `/docs/`
  * `ALIFE2026_Preprint.pdf`: Manuscript draft.

## 🚀 Usage & Reproducibility
To reproduce Figures A and B from the original paper:
1. Open `Zurvan_Phase_Diagram.nb` in Wolfram Mathematica (v12+).
2. Base parameters are pre-calibrated for the high-friction *P. putida* phenotype:
   - Conformational scale $T_0 = 260\text{ K}$
   - Active unit limit $N_{max} = 11$
   - $Z_c$ calibrated for a cold-collapse at $81.9\text{ Hz}$.
3. Executing the notebook will generate the overlay of the three operational temperatures (277K, 290K, 303K), exposing the Zurvān Gap.

## 🔬 The Experimental Challenge 
This model is not a post-hoc metaphor; it is a falsifiable thermodynamic prediction. The mathematics dictate that high-friction architectures like MotAB must undergo population-level disassembly at moderately high speeds. 

We challenge the experimental biophysics community to put these postulates to the test on the optical table using single-motor microscopy via IR T-Jumps or membrane FRAP experiments. Measure the turnover rate ($k_{off}$) exactly at the macroscopic torque knee. You will witness the collapse of the Thermodynamic Wedge.

---
*Maintained by Glyxon Biolabs - Independent Research & Frugal Science.*# Zurvatronics

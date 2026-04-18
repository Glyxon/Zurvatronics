# Glyxon-Zurvatronics ⚙️🧬
**Analytical Models of Subtractive Ontology and Informational Collapse in Molecular Motors**

**Author:** David J. Castillo-Cornejo (2026)  
**Affiliation:** Synthetic Biosystems Lab, Glyxon Biolabs  
**Contact:** [glyxonbiolabs@gmail.com](mailto:glyxonbiolabs@gmail.com)

[![ALIFE](https://img.shields.io/badge/ALIFE-2026-blue.svg)](https://alife.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

<div align="center">
  <h2>🎮 Interactive Simulations</h2>
  <p>Explore the transition from population-level phase diagrams to single-stator micro-mechanics.</p>
  
  <table>
    <tr>
      <td align="center">
        <strong>1. Population Collapse (Zurvān Gap)</strong><br>
        <a href="https://glyxon.github.io/Zurvatronics/interactive_sim/">
          <img src="https://img.shields.io/badge/-START_PHASE_SIM-121212?style=for-the-badge&logo=matrix&logoColor=2ECC71" alt="Phase Sim">
        </a>
      </td>
      <td align="center">
        <strong>2. Micro-Mechanics (Power Stroke)</strong><br>
        <a href="https://glyxon.github.io/Zurvatronics/interactive_sim/power_stroke.html">
          <img src="https://img.shields.io/badge/-START_POWER_STROKE-121212?style=for-the-badge&logo=matrix&logoColor=4DA8DA" alt="Power Stroke Sim">
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 👁️ The Subtractive Agency Manifesto
Zurvatronics proposes an inhibitory framework: directionality emerges from the **systematic subtraction of informational entropy**. Molecular machines do not compute to move; they compute to persist. 

## 🧮 Theoretical Core: The Zurvān Gap
The MotAB stator is modeled as an informational filter. The **Zurvān Gap** is the temperature-dependent window where the "Thermodynamic Wedge" (the margin between Catch-Bond stability and thermal noise) collapses.

## ⚙️ Micro-Mechanics: Stick-Slip & Power Stroke
While the Phase Diagram shows population stability, the Java-based **Stick-Slip model** describes the lifecycle of a single stator:
* **The Stick Phase ($Z \uparrow$):** Structural tension accumulates as the stator "prunes" stochastic paths, restricting rotor speed to store potential information.
* **The Slip Phase ($Z \ge Z_c$):** Upon reaching the critical threshold, the informational anchor collapses, triggering an instantaneous release of energy—the **Power Stroke**.

## 📜 Theoretical Foundation & Mathematical Formalism
The computational models in this repository are grounded in the subtractive ontology framework presented in the ALIFE 2026 manuscript. The model unifies Shannon information theory with stochastic thermodynamics to explain biological agency.

### 1. The Swineshead Latitudo $L(T)$
The instantaneous filtering capacity of the stator is defined by the energy invested by its physical topology to maintain conformational restriction. Drawing from Richard Swineshead's medieval intensity calculus, the Latitudo is formalized as:
$$L(T) = k_B T \ln(2) \cdot [H_{max} - H(S,T)]$$
Where $H_{max}$ is the maximum Shannon entropy, and $H(S,T)$ is the actual entropy of the stator. The framework demonstrates that $L(T)$ peaks in cold (psychrotrophic) environments, explaining the high filtering precision of *Pseudomonas putida* at low temperatures.

### 2. The Zurvān Coefficient $Z$
Agency emerges from the temporal accumulation of this filtering capacity over the proton's residence time ($\tau_{res}$) within the MotAB channel:
$$Z = \int_{0}^{\tau_{res}} L(T,t) dt$$
$Z$ possesses the dimensions of physical action (Joules $\cdot$ seconds). As rotational speed increases, $\tau_{res} \rightarrow 0$, causing $Z$ to drop below the critical threshold ($Z_c$) required for catch-bond activation. The motor does not fail mechanically; it runs out of time to compute its existence.

### 3. The Inhibitory Operator (Modified Langevin Dynamics)
To bridge information theory and classical biophysics, we introduce the inhibitory operator $\Psi_Z(t)$ as an additive counter-force in the Generalized Langevin Equation:
$$m \frac{dv}{dt} = F_{PMF} - \eta v - [P_{assembly} \cdot \Psi_Z(t)] + \xi(t)$$
Where the informational penalty is $\Psi_Z(t) = \kappa \cdot Z(t) \cdot \tau_{res}$. The motor generates a power stroke not by adding force, but by the sudden collapse of this informational penalty ($P_{assembly} \rightarrow 0$) when the critical action $Z_c$ is reached.

### 4. Resolving the Zero-Load Controversy
This mathematical framework provides a predictive resolution to the conflicting zero-load observations (Nirody vs. Wang). The near-zero load regime is identified as a zone of fundamental informational instability ($\zeta \approx 1$), where the system hovers on the sigmoidal boundary of $P_{assembly}$, making macroscopic dynamics hypersensitive to marginal experimental drag.  

## 📂 Repository Architecture
* `/interactive_sim/`: JS-based visualizers for Phase Transitions and Power Stroke dynamics.
* `/src/java_models/`: `PowerStrokeSim.java` - High-performance Euler-Maruyama integrator for single-stator kinetics.
* `/src/mathematica/`: Analytical notebooks for the *Latitudo formarum* and Figures A/B.
* `/docs/`: `Castillo-Cornejo_ALIFE2026-FINAL.pdf` - Full theoretical manuscript.

## 🔬 Experimental Challenge
We challenge the community to measure the stator turnover rate ($k_{off}$) at the macroscopic torque "knee". The predicted synchronization between $Z$ collapse and velocity spikes provides a falsifiable signature of Subtractive Agency.

## ⏳ Philosophical Context: Why "Zurvatronics"?
The nomenclature of this framework is derived from **Zurvanism**, an extinct branch of Zoroastrianism that posited *Zurvān* (Infinite Time) as the primordial creator. In this mythology, light (order) and darkness (chaos) do not exist independently; they are subsequent bifurcations born from the passage of time.

This philosophical lens perfectly mirrors the subtractive ontology of molecular motors: 
Biological agency is not a "vital spark" injected into matter. Instead, the motor (the agent) uses its physical structure to "buy time" ($\tau_{res}$), filtering out thermal chaos to allow directional order to emerge. The **Zurvān Coefficient ($Z$)** is literally the mathematical measurement of how much "time" a system has successfully converted into informational order before collapsing into entropy.

---

## 🗺️ The Zurvatronic Roadmap: Future Extensions
The current framework establishes the baseline for the *Pseudomonas putida* MotAB stator. However, the theoretical implications of Subtractive Agency point toward a much broader research program. Glyxon Biolabs is currently exploring three progressively ambitious extensions:

### 1. Zurvatronic Taxonomy of Molecular Machines
If every molecular motor possesses a characteristic Critical Threshold ($Z_c$) and a minimum required residence time ($\tau_{min}$), we can build a new classification system based on informational parameters rather than structural families. 
* **High $Z_c$ Regimes:** Classical, highly stable, deterministic motors.
* **Near $Z_c$ Regimes:** Sensitive, adaptive machines hovering on the edge of informational collapse (e.g., the flagellar motor at zero-load).
* **Synthetic Application:** Designing artificial nanomotors not by copying structural blueprints, but by targeting specific $Z_c$ thermodynamic regimes.

### 2. Thermodynamic Theory of Agency Emergence (Abiogenesis)
How does agency emerge from non-agency? Under the Zurvatronic lens, the transition from complex chemistry to biological life is the exact moment a molecular topology accumulates sufficient action ($Z$) to cross its $Z_c$ threshold, becoming self-stabilizing. Life does not merely "explore" the adjacent possible; it *earns access to it* by computing against its own decoherence. This provides a falsifiable, mathematical mechanism for the origin of life.

### 3. Hierarchical Zurvatronics & Cognition (The Deepest Extension)
The logic of Subtractive Agency scales. If agency at the molecular level is the suppression of decoherent conformational states (Zurvatronics), then agency at the cognitive level is the suppression of decoherent representational states—which aligns perfectly with Karl Friston’s **Free Energy Principle** and predictive coding. 

We propose that the Swineshead Latitudo and the $Z$ coefficient can be generalized across all levels of biological organization—from proton transit in a stator channel, to action potential generation in a neuron, to predictive inference in a cortical circuit. 
> *A molecular machine does not compute in order to move; it computes to persist. Similarly, a brain does not compute in order to perceive; it computes to persist as a coherent self-model against the entropic noise of reality.*

---
*Maintained by Glyxon Biolabs - "Frugal Science for Subtractive Ontology."*

---
*Maintained by Glyxon Biolabs - Independent Research & Frugal Science.*

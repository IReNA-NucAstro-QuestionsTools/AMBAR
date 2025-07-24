# ¹²C + ¹²C → ²⁴Mg Nuclear Reaction Study

## Table of Contents
- [Team Members](#team-members)
- [Objectives](#objectives)
- [Experimental Procedure](#experimental-procedure)
- [Results](#results)

---

## Argentina-México-Brasil Astrophysics Research (AMBAR) members:
- Jessica Chaves
- Jorge Gomez
- Araceli Garcia Flores

---

## Objectives
1. Investigate the cross-section (σ) of the ¹²C + ¹²C → ²⁴Mg reaction in the center-of-mass energy range 1–5 MeV.
2. Analyze influence of excited states on the fusion cross-section.
3. Compare experimental data with theoretical predictions or literature values.

---

## Procedure
To study the ¹²C + ¹²C → ²⁴Mg reaction, we used the FRESCO code [ref] to first analyze the elastic scattering channel, without including any excited states. This was done to evaluate whether the São Paulo Potential (SPP) [ref] provides an adequate description of the real part of the interaction for this system.

Next, we introduced an internal imaginary Wood-Saxon potential (WSP)[ref] to account for fusion. We used standard parameters:
V = 50 MeV, r = 1.0 fm, and a = 0.20 fm, while retaining the real part of the SPP.

After establishing this baseline, we gradually included excited states for both the projectile and the target, up to the third excited state. Due to the low cross sections observed for inelastic channels within the studied energy range, we did not consider additional couplings to higher-lying states.

In this final stage, we kept the internal WSP and added the imaginary part of the SPP to model surface-level reaction mechanisms, such as inelastic scattering.

---

## Results
![Preliminar](/plots/test.png)

## Repository Structure

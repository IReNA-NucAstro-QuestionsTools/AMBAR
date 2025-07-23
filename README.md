# ¹²C + ¹²C → ²⁴Mg Nuclear Reaction Study

## Table of Contents
- [Team Members](#team-members)
- [Objectives](#objectives)
- [Experimental Procedure](#experimental-procedure)
- [Results](#results)

---

## Team Members
- **Name 1** – Role (e.g., Principal Investigator)
- **Name 2** – Role (e.g., Data Analysis)
- **Name 3** – Role (e.g., Experimental Setup)

---

## Objectives
1. Investigate the cross-section (σ) of the ¹²C + ¹²C → ²⁴Mg reaction in the center-of-mass energy range 2–5 MeV.
2. Determine the astrophysical S-factor as a function of energy.
3. Analyze resonant structures or enhancements in reaction yield.
4. Compare experimental data with theoretical predictions or literature values.

---

## Experimental Procedure
1. **Beam Preparation**  
   Accelerate a ¹²C ion beam to desired energies (E_cm from 2–5 MeV).
2. **Target Setup**  
   Utilize a high-purity carbon target (~100 µg/cm² thickness).
3. **Detection System**  
   Deploy silicon detectors and/or gas detectors at laboratory angles to detect outgoing ²⁴Mg nuclei or alpha products.
4. **Calibration**  
   Calibrate detector energy response using known alpha sources or reference reactions.
5. **Data Acquisition**  
   - Record beam current, incident energy, and detection counts.
   - Measure background runs for subtraction.
6. **Data Analysis**  
   - Subtract background from signal counts.
   - Correct for detection efficiency and target thickness.
   - Compute cross-sections σ(E) using standard formula:
     ```
     σ = (Yield) / (Beam current × Target density × Efficiency)
     ```
   - Derive S-factor:  
     ```
     S(E) = σ(E) × E × exp(2π η)
     ```
     where η is the Sommerfeld parameter.
7. **Uncertainty Estimation**  
   Propagate statistical (counting) and systematic (efficiency, thickness, beam current) errors.

---

## Results
| E_cm (MeV) | σ (mb)        | S-factor (10¹⁵ MeV·b) |
|------------|---------------|------------------------|
| 4.93 ± 0.07 | 4.8 ± 0.9    | 2.8 ± 0.5              |
| 4.80 ± 0.07 | 2.0 ± 0.4    | 1.9 ± 0.4              |
| 4.73 ± 0.07 | 0.88 ± 0.17  | 1.1 ± 0.2              |
| ⋮          | ⋮             | ⋮                      |

- **Data visualization**: include plots like σ(E) and S(E) vs E_cm (you can store e.g. `plots/Sfactor_vs_E.png`).
- **Resonant behavior**: comment on any peaks or anomalies observed within the range.
- **Comparison**: juxtapose your findings with published data if available.

---

## Repository Structure

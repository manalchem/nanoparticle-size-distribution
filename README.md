# Nanoparticle Size Distribution Analysis
## Chemical Engineering Portfolio Project

A Python simulation modeling nanoparticle size distributions for tissue engineering 
and biomaterials applications, built in Google Colab.

---

## Overview
Models how synthesis temperature affects nanoparticle size distribution using:
- Log-normal distribution fitting (standard model for synthesized nanoparticles)
- Statistical characterization metrics used in real lab settings (DLS analysis)
- Polydispersity Index (PDI) calculation across multiple synthesis conditions

---

## Key Results
| Condition | Mean Size (nm) | Std Dev | PDI |
|-----------|---------------|---------|-----|
| Low Temp | 86.4 | 36.6 | 0.180 |
| Mid Temp | 45.8 | 11.3 | 0.061 |
| High Temp | 20.1 | 3.1 | 0.023 |

Higher synthesis temperature produces smaller, more monodisperse nanoparticles.
PDI < 0.1 indicates well-controlled synthesis — critical for tissue engineering composites.

---

## Relevance
This analysis mirrors characterization workflows used in biomaterials research labs,
including Dynamic Light Scattering (DLS) data interpretation and synthesis optimization
for functional composite development in tissue engineering applications.

---

## Tools
Python · NumPy · Matplotlib · SciPy · Google Colab

---

## Author
Manal | Chemical Engineering Student | github.com/manalchem

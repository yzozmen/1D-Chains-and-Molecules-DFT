# 1D-Chains-and-Molecules-DFT
DFT study of molecules and one-dimensional atomic chains using VASP.

# 1D Chains and Molecules DFT Study

DFT-based structural analysis of molecular systems and one-dimensional atomic chains using VASP.

This repository documents selected results from a computational materials science project, including geometry optimization, convergence testing, cohesive-energy calculations, and electronic-structure analysis.

## Molecules

### H₂O

#### Optimized Geometry

The H₂O molecule was structurally optimized using VASP.

Calculated structural parameters:

| Property | Calculated |
|---|---:|
| O-H bond length | 0.9720 Å |
| H-O-H bond angle | 104.5341° |

![Optimized H2O geometry](figures/molecules/h2o/h2o_optimized_geometry.png)

#### Linear Configuration

A linear H₂O configuration was also investigated for comparison.

| Property | Calculated |
|---|---:|
| O-H bond length | 0.9425 Å |
| H-O-H bond angle | 180.00° |

![Linear H2O geometry](figures/molecules/h2o/h2o_linear_geometry.png)

#### ENCUT Convergence

The effect of plane-wave cutoff energy on the calculated total energy was examined to determine an appropriate computational parameter.

![H2O ENCUT convergence](figures/molecules/h2o/h2o_encut_energy.png)

## Data Availability

The original calculations were performed using VASP on an HPC system during a research internship.

The original raw VASP input and output files are currently unavailable. This repository therefore contains preserved numerical results, figures, and reconstructed data tables derived from the original project records.

## Tools

- VASP
- VESTA
- Python


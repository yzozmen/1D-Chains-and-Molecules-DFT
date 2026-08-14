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

### CO₂

#### Optimized Geometry

The CO₂ molecule was structurally analyzed using VASP.

Calculated structural parameters:

| Property | Calculated |
|---|---:|
| C-O bond length | 1.176 Å |
| O-C-O bond angle | 180.0° |

![CO2 geometry](figures/molecules/co2/co2_geometry.png)

#### ENCUT Convergence

The dependence of the total energy on the plane-wave cutoff energy was examined.

![CO2 ENCUT test](figures/molecules/co2/co2_encut_test.png)

#### Vacuum Convergence

The effect of the simulation-cell vacuum size on the calculated total energy was also investigated.

![CO2 vacuum test](figures/molecules/co2/co2_vacuum_test.png)

#### Cohesive Energy

The preserved project results give a calculated cohesive energy of:

**E_coh = -18.538 eV**



## Data Availability

The original calculations were performed using VASP on an HPC system during a research internship.

The original raw VASP input and output files are currently unavailable. This repository therefore contains preserved numerical results, figures, and reconstructed data tables derived from the original project records.

## Tools

- VASP
- VESTA
- Python






**Computational Analysis of Ni₃Al Superalloy Using DFT (SCF + VC-Relax)**
**1. Project Overview**

This repository contains the input and output files for a Density Functional Theory (DFT) study of Ni₃Al, an important intermetallic compound used in high-temperature superalloy applications, particularly in aerospace turbine blades, jet engines, and advanced metallurgical systems.

The primary goal of this project was to determine the ground-state structural properties, total energy, Fermi energy, and magnetization behavior of Ni₃Al using first-principles calculations. The stable L1₂-ordered phase of Ni₃Al was used as the basis for all simulations.

**2. Methodology**

The workflow for this project integrates crystallographic databases and state-of-the-art first-principles simulation methods.

2.1. Structure Identification

The initial L1₂ crystal structure of Ni₃Al (Cu₃Au prototype) was adopted from established intermetallic datasets and verified for correct stoichiometry and symmetry.
This L1₂ structure is well documented for its mechanical strength, creep resistance, and oxidation behavior—making accurate DFT characterization crucial for metallurgical engineering.

**2.2. DFT Simulation**

All simulations were performed using Quantum ESPRESSO (QE) within a Linux/WSL environment. The computational workflow included:

Calculation Types:

vc-relax for full optimization of lattice parameters and internal atomic positions.

scf for determining electronic ground-state properties, Fermi level, and magnetization.

**Convergence Techniques:**
Metallic smearing using the Methfessel–Paxton scheme was used to ensure smooth electronic convergence.

Analysis:
Key parameters—including total energy, Fermi energy, optimized cell dimensions, and spin-related properties—were extracted from the QE output files.
Energy convergence behavior was later visualized using tools such as gnuplot or Python-based plotting.

---
layout: posterpage
categories: [poster]
posternumber: P26
speaker: Tatiana Nikolaeva
location: 'Technical University of Munich · Department of Chemistry · Munich (DE)'
title: "Improving ion-water electrostatics in tight-binding methods for simple electrolyte solutions"
authors: 'T. Nikolaeva, H. J. Kulik, C. J. Stein'
abstract: [
"Simulating the solvation structure of electrolyte solutions, with its subtle interactions and ion-pairing patterns, is a fundamental challenge for developing efficient energy conversion devices. Accurate density functional theory (DFT) is computationally costly for large-scale and long-time simulations. A less expensive alternative is provided by the density functional based tight binding (DFTB) methods. However, it has been observed previously that DFTB-driven molecular dynamics (MD fails to correctly predict crucial properties for electrolyte solutions, such as ion interactions, solvation structure [1, 2], or hydrogen bond network [3].
To explore the applicability of DFTB methods to MD and improve their reliability, we establish a DFTB reparameterization workflow targeting specifically the dynamic properties of simple electrolyte solutions. We propose a reparameterization workflow for the GFN2-xTB DFTB variant [4] in order to enhance the DFTB-MD performance for aqueous sodium chloride solutions. In the optimization protocol, we fit the interaction energies, atomic forces, and molecular dipole moments of water molecules to the wB97M-V/def2-TZVP DFT level for a chemically motivated dataset of non-periodic clusters of water, hydrated sodium, and chlorine isomers. We employ both scalar and multiobjective optimization methods, benchmark them, and investigate their generalizability for describing non-fitted physical properties of hydrated NaCl. Using the resulting optimized parameters, we perform DFTB-MD simulations of NaCl water solution and compute structural and transport observables, including radial distribution functions and corresponding coordination numbers, hydrogen bond statistics and lifetimes, and self-diffusion coefficients. We evaluate the reparameterization performance by comparing those properties against experimental data and ab initio MD benchmarks.
With this, we enhance the accuracy of DFTB methods in application to the simulation of simple electrolytes, making it an efficient, low-cost alternative to ab initio MD with DFT"]
references: [
['P. Wróbel; P. Kubisiak; A. Eilmes', 'J. Phys. Chem. B 2021', '125', '4', '1248'],
['P. Wróbel; A. Eilmes', 'Molecules 2023', '28', '18', '6736'],
['X. Wu; H. Elgabarty; V. Alizadeh; A. Henao; F. Zysk; C. Plessl; S. Ehlert; J. Hutter; T. D. Kühne', 'arXiv preprint 2025', 'arXiv:2503.11867'],
['C. Bannwarth; S. Ehlert; S. Grimme', 'J. Chem. Theory Comput. 2019', '15', '3', '1652']
]
---

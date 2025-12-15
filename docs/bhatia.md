---
layout: posterpage
categories: [poster]
posternumber: P34
speaker: Nitik Bhatia
location: 'Technical University of Munich · Department of Physics · Munich (DE)'
title: "MACE4IRmol A foundation model for molecular infrared spectroscopy"
authors: 'N. Bhatia, O. Krejci, S. Botti, P. Rinke, M. Marques'
abstract: [
"Infrared (IR) spectroscopy is a powerful tool for probing molecular vibrations, identifying functional groups, molecular structures, and reaction intermediates. However, accurate IR spectra prediction typically relies on density functional theory (DFT), which is computationally prohibitive for high-throughput applications. To overcome this limitation, we present MACE4IRmol, a foundation machine learning model based on the MACE architecture [1] and trained on ~16M DFT-calculated molecular geometries from the QCML dataset [2], spanning nearly 80 elements and encompassing a broad chemical space of organic, inorganic, and transition-metal–containing molecules. The QCML dataset provides highly accurate energies, forces, and dipole moments computed with the hybrid PBE0 [3] exchange–correlation functional, together with reference data for D4 [4] and many-body dispersion [5] van der Waals corrections. Leveraging this comprehensive dataset, we offer models trained on pure DFT (PBE0) data as well as models that explicitly incorporate these dispersion corrections. To further ensure robustness and enable uncertainty estimation, we also provide ensembles of independently trained models.<br><br>
MACE4IRmol achieves high accuracy below 3 meV/atom for energies, 30 meV/Å for forces, and 25 meÅ for dipole moments and predicts harmonic vibrational frequencies with errors of ~40 cm⁻¹ relative to DFT. In addition to harmonic analysis, the model enables fast and reliable IR spectra from classical molecular dynamics, delivering 4–5 orders of magnitude speedup over conventional first-principles approaches. Furthermore, MACE4IRmol supports quantum nuclear effects via path-integral molecular dynamics [6], allowing accurate treatment of systems where nuclear delocalization or tunneling plays a critical role. Together, these capabilities establish MACE4IRmol as an efficient, versatile, and highly accurate platform for IR spectra prediction across chemistry, biology, and materials science."]
references: [
['I. Batatia et al.', 'Adv. Neural Inf. Process. Syst. 2022', '35', '11423–11436'],
['S. Ganscha et al.', 'Sci. Data 2025', '12', '406'],
['J. P. Perdew et al.', 'J. Chem. Phys. 1996', '105', '9982–9985'],
['E. Caldeweyher et al.', 'J. Chem. Phys. 2019', '150', '154122'],
['A. Tkatchenko et al.', 'Phys. Rev. Lett. 2012', '108', '236402'],
['M. Ceriotti et al.', 'J. Chem. Phys. 2011', '134', '84104'; 'Comp. Phys. Comm. 2014', '185 (3)', '1019']
]
---

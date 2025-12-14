---
layout: posterpage
categories: [poster]
posternumber: P30
speaker: Lisa Hetzel
location: 'Technical University of Munich · School of Natural Sciences · Munich (DE)'
title: "IBenchmarking small and efficient machine-learning interatomic potentials for aqueous electrolyte solutions"
authors: 'L. Hetzel, C. J. Stein'
abstract: [
"Modeling solid–liquid interfaces containing electrolytes is challenging because the electric double layer involves complex long-range interactions and non-local charge-transfer effects that require quantum-chemical accuracy. These features require extensive sampling, making ab initio methods impractical. Machine-learning interatomic potentials (MLIPs) have revolutionized molecular dynamics simulations, and numerous architectures - starting from Behler’s high-dimensional neural network potentials (HDNNPs) [1] - have improved both data efficiency and accuracy. MACE [2], for example, introduces an equivariant message-passing framework that not only increases accuracy compared to invariant models but also incorporates effectively longer-ranged interactions, whereas conventional MLIPs cannot see beyond their cutoff radius. Although explicit long-range corrections such as Cheng’s latent Ewald summation [3] or Behler’s 3rd- and 4th-generation HDNNPs [4,5] exist, they add additional computational cost, making message-passing models an attractive compromise for systems with screened interactions.
At the same time, foundation models such as UMA [6] or the MACE [7] variants are becoming increasingly popular due to their broad chemical generality. However, their large and diverse training datasets require large models, making them computationally heavy and limiting their accessibility. Hence, small and dedicated models can serve as a sustainable alternative to reduce computational cost, particularly when GPU resources are limited. In this study, we systematically explore how model hyperparameters, such as the number of trainable parameters and the level of equivariance, affect both accuracy and computational cost. We further examine how fitting errors propagate to physical observables, including solvation structure and diffusion coefficients. We find that while the final accuracy has only a minor impact on converged physical quantities, it strongly affects model stability, which ultimately limits the achievable sampling time. Our results thus provide practical guidelines for designing small but robust MLIPs for aqueous electrolyte simulations. [8]"]
references: [
['J. Behler; M. Parrinello', 'Phys. Rev. Lett. 2007', '98', '146401'],
['I. Batatia; D. P. Kovács; G. N. C. Simm; C. Ortner; G. Csányi'; '2022'],
['B. Cheng', 'Npj Comput. Mater. 2025', '11', '80'],
['T. W. Ko; J. A. Finkler; S. Goedecker; J. Behler', 'Acc. Chem. Res. 2021', '54', '808'],
['N. Artrith; T. Morawietz; J. Behler', 'Phys. Rev. B 2011', '83', '153101'],
['B. M. Wood; M. Dzamba; X. Fu; M. Gao; M. Shuaibi et al.', 'arXiv Preprint 2025', 'arXiv:2506.23971'],
['I. Batatia; P. Benner; Y. Chiang; A. M. Elena; D. P. Kovács et al.', 'J. Chem. Phys. 2025', '163', '184110'],
['L. Hetzel; C. J. Stein', 'ChemRxiv preprint 2025', 'DOI:10.26434/Chemrxiv-2025-2jdsh']
]
---

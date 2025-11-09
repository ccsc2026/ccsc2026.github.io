---
layout: talkpage
categories: [keynote]
talknumber: D10
talktime: '10.-13.03.2026, 15:00 – 15:30'
speaker: Dr. Johannes Hoja
img: 'Hoja, Johannes.png'
location: 'University of Graz · Department of Chemistry · Graz (AT)'
title: 'Exploring Solid-State Reactions and Polymorph Interconversions in Molecular Crystals with Machine-Learned Force Fields'
authors: 'J. Hoja'
abstract: [
"Gaining quantitative insight into the dynamics and kinetics of molecular crystals is vital for drug development and for advancing solvent-free, sustainable synthesis methods that rely on solid-state reactions. However, this remains a difficult task as molecular crystals often exhibit multiple polymorphs that differ by only a few kJ/mol in their Gibbs free energies while other properties can be significantly different. Thus, a reliable description of these polymorphs requires very accurate calculations to correctly capture their relative stabilities [1].
Herein, we explore energy barriers and transition pathways of molecular crystal transformations, covering interconversions between polymorphs and single-crystal Diels-Alder reactions. Since density functional theory (DFT) calculations are often already prohibitively expensive for these kind of simulations, we utilize machine-learned force fields (MLFFs) based on the SO3KRATES neural network [2] and the SO3LR method [3] to massively speed up the calculations while still maintaining near-DFT accuracy. First, we focus on solid-state nudged elastic band (NEB) calculations for several molecular crystal transformations, for which we utilize a novel interpolation method for automatically generating viable initial pathways that avoids atomic collisions in complex molecular crystals [4]. Next, we discuss the applicability of the MLFFs for calculating vibrational free energies, which are needed for obtaining Gibbs free energy differences between the initial structures and the transition states. Finally, we also utilize MLFFs to perform explicit molecular dynamics simulations for several transformations and compare to our direct NEB results. Collectively, these advances will bring us closer to a comprehensive, computationally efficient picture of polymorph transformation pathways and reaction mechanisms in molecular crystals."
]
references: [
['J. Hoja; H.-Y. Ko; M. A. Neumann; R. Car; R. A. DiStasio Jr.; A. Tkatchenko', 'Sci. Adv. 2019', '5', 'aau3338'],
['J. T. Frank; O. T. Unke; K.-R. Müller; S. Chmiela', 'Nat. Commun. 2024', '15', '6539'],
['A. Kabylda et al.', 'J. Am. Chem. Soc. 2025', '147', '33723–33734'],
['N. Goncharova, J. Hoja', 'J. Chem. Phys. 2025', 'arXiv:2410.10506']
]
---

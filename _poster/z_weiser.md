---
layout: posterpage
categories: [poster]
posternumber: P50
speaker: Jonas Weiser
location: 'University of Augsburg · Department of Theoretical Physics · Augsburg (DE)'
title: "Towards automated ensemble-averaged kinetics of reverse intersystem crossing in flexible TADF emitters"
authors: 'J. Weiser, C. Wiebeler'
abstract: [
"Thermally activated delayed fluorescence (TADF) is a cornerstone of third generation OLED design, enabling up to 100% internal quantum efficiency through reverse intersystem crossing (RISC).[1] However, in flexible donor-acceptor systems, RISC rates are sensitive to geometry-dependent fluctuations in energy gaps and spin-orbit couplings (SOCs).[2] Traditional static models relying on single optimized geometries often fail to capture the experimental reality of these flexible molecules, as they not only ignore the distribution of accessible excited-state conformations but also RISC pathways governed by higher-order spin-vibronic coupling via intermediate higher triplet states[3].

To address this, we present an automated multi-scale quantum-chemical workflow that moves beyond static geometry approximations and bridges the gap between microscopic structural dynamics and macroscopic kinetic rates. The pipeline integrates large-scale metadynamics sampling[4] of S1 and T1 states as well as S1–T2 crossings[5] with structural clustering to identify key representative macrostates. We then employ efficient electronic structure theory[6] to refine geometries, energies, and SOC matrix elements across the resulting conformational space.

Integrating these local contributions, our approach calculates the global RISC rate as a Boltzmann-weighted sum of all local direct and T2-mediated pathways. This framework accurately captures molecular flexibility and provides a physically rigorous and scalable tool for the reliable prediction of TADF RISC rates across a diverse chemical space."]
references: [
['C. Adachi', 'Jpn. J. Appl. Phys. 2014', '53', '060101'],
['J. Kaminski; T. Böhmer; C. Marian', 'J. Phys. Chem. C 2024', '128', '13711-13721'],
['A. Morgenstern; J. Weiser; L. Schreier; K. Gabel; T. Gabler; A. Ehm; D. Beer; N. Schwierz; U. Schwarz; K. Zeitler; C. Deibel; D. Zahn; C. Wiebeler; G. Salvan', 'Advanced Optical Materials 2025', '14', 'e01504'],
['P. Pracht; S. Grimme; C. Bannwarth; F. Bohle; S. Ehlert; G. Feldmann; J. Gorges; M. Müller; T. Neudecker; C. Plett; S. Spicher; P. Steinbach; P. Wesołowski; F. Zeller', 'The Journal of Chemical Physics 2024', '160', '114110'],
['P. Pracht; C. Bannwarth', 'J. Phys. Chem. Lett. 2023', '14', '4440-4448'],
['S. Grimme; J. Brandenburg; C. Bannwarth; A. Hansen', 'The Journal of Chemical Physics 2015', '143', '054107']
]
---

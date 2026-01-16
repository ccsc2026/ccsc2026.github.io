---
layout: posterpage
categories: [poster]
posternumber: P54
speaker: Gabriel Rottkemper
location: 'LMU Munich · Department of Chemistry · Munich (DE)'
title: "Accelerating Ab Initio Molecular Dynamics Liquid Water Simulations with Message Passing Neural Networks"
authors: 'G. Rottkemper, V. Isukapalli, D. Ho, S. Reiter, B. P. Fingerhut'
abstract: [
"Ab initio molecular dynamics (AIMD) simulations allow for a theoretical analysis of complex systems and chemical reactions with high accuracy. Since AIMD evaluates forces on atoms from quantum mechanical calculations with electron repulsion integrals at each time step of a molecular dynamics (MD) simulation, the resulting computational cost is substantial. The application of machine learning potentials, based on Neural Networks (NN), to accelerate MD simulations has thus great potential, provided that the accuracy of an AIMD simulation is maintained.
The structure and dynamics of liquid water is determined by covalent bonding interactions, intermolecular hydrogen bonds and van-der-Waals interactions. To gain highly accurate insight into the properties of liquid water, ab initio simulations are necessary to correctly simulate the subtle balance of inter- and intramolecular degrees of freedom at thermal equilibrium, requiring substantial computational resources.
In this contribution, we investigate the potential of NNs and especially higher order Message Passing NNs like PaiNN or MACE, to reduce the simulation time of AIMD simulations. Periodic boxes of liquid water with different sizes, simulated with two highly accurate density functional theory XC-functionals (PW6B95-D3 and revPBE0-D3) serve as training set. With PW6B95-D3, we successfully trained a force field on small box sizes, that is able to scale to different and larger system sizes, while maintaining accuracy. In contrast, for revPBE0-D3, we identify size-dependent structural artefacts that raise the challenge of reproducibility with a Neural Network."]
---

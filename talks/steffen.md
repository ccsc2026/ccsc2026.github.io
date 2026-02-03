---
layout: talkpage
categories: [contrib]
talknumber: D2.11
talktime: '11.03.2026, 17:20 – 17:40'
speaker: Dr. Julien Steffen
img: 'Steffen, Julien.png'
location: 'Friedrich-Alexander-Universität Erlangen-Nürnberg · Department of Chemistry · Erlangen (DE)'
title: "Self-Consistent Fine-Tuning of Machine Learning Interatomic Potentials by Targeted Exploration of Configuration Space"
authors: 'J. Steffen'
abstract: [
"Universal machine learning interatomic potentials (uMLIPs) have shown an astonishing ability of describing almost arbitrary chemical systems reasonably. 
They are, however, not accurate enough for the calculation of quantities like reaction rate constants that require a very precise representation of the potential energy surface. 
Fortunately, uMLIPs can be fine-tuned for a system of interest, by training them on system-specific ab initio reference data. The generation of such reference data is nontrivial 
since it requires a broad sampling of the relevant configuration space, often out of each for direct ab initio molecular dynamics (AIMD) [1]. Self-consistent fine-tuning is a 
solution for this: long MD samplings are done with the uMLIP, a relevant subset of sampled structures is recalculated with the ab initio method, and this is iterated with the 
successively fine-tuned MLIP to cure the slightly incorrect configurational sampling of the uMLIP [2].
<br>
In this contribution, I show how self-consistent fine-tuning of uMLIPs can be combined with umbrella samplings along complex reaction coordinates with the Caracal program [3]. 
This enables the black-box setup of highly accurate targeted MLIPs for different chemical reaction mechanisms in arbitrary environments. I present the application of this method 
on two examples: proton exchange reactions in the gas phase and hydrogen diffusion on different metal surfaces, both treated with ring polymer molecular dynamics (RPMD) to consider 
nuclear quantum effects. Further, an outlook is given on how to generalize the method to arbitrary chemical systems and reaction mechanisms.
"]
references: [
['J. Steffen; A. Alibakhshi', 'J. Chem. Phys. 2024', '161', '184116'],
['J. Steffen', 'J. Phys. Chem. C 2025', '129', '13513'],
['J. Steffen', 'J. Chem. Theory Comput. 2023', '19', '5334']
]
---

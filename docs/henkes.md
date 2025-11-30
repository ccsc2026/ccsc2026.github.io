---
layout: posterpage
categories: [poster]
posternumber: P21
speaker: Tobias Henkes
location: 'University of Luxembourg · Department of Physics and Materials Science · Luxembourg (LU)'
title: "aims-PAX: The Parallel Active Exploration Tool for Peace of Mind in Constructing Machine Learning Force Fields"
authors: 'T. Henkes, S. Sharma, A. Tkatchenko, M. Rossi, I. Poltavskyi'
abstract: [
"In recent years, machine learning force fields (MLFFs) [1] have transformed molecular simulations. While pre-trained models are increasingly capable, there remains a strong demand for information-rich datasets to fine-tune general-purpose models or create custom ones for challenging applications.
<br><br>
To this end, we introduce the ab initio molecular simulation Parallel Active eXploration (aims-PAX) package [2], an automated framework for constructing diverse and high-quality datasets for training MLFFs through active learning (AL). This software combines the electronic structure code FHI-aims [3] with MLFFs, offering a user-friendly approach for efficient dataset creation. Through a parallelized, automated AL algorithm that leverages simultaneous sampling across multiple trajectories, our approach minimizes user intervention and optimizes computational resource use across CPU and GPU architectures.
<br><br>
We demonstrate aims-PAX`s capabilities across a range of challenging scenarios: generating a dataset and accurate models for a highly complex peptide, while dramatically lowering computational cost; autonomously identifying challenging systems within a defined chemical space; and enabling the simulation of solvated molecules comprising over 1,000 atoms by seamlessly handling both periodic and aperiodic systems. Lastly, we highlight the superior computational efficiency of the parallelized procedure on a perovskite system. In total, these results establish aims-PAX as a powerful and versatile tool for advanced ML-driven atomistic simulations in both academic and industrial contexts.]
references: [
['O. T. Unke; S. Chmiela; H. E. Sauceda; M. Gastegger; I. Poltavsky; K. T. Schütt; A. Tkatchenko; K.-R. Müller', 'Chemical Reviews 2021', '121'],
['T. Henkes; S. Sharma; A. Tkatchenko; M. Rossi; I. Poltavskyi', 'arXiv:2508.12888'],
['V. Blum; R. Gehrke; F. Hanke; P. Havu; V. Havu; X. Ren; K. Reuter; M. Scheffler', 'Computer Physics Communications 2009', '180', '2175–2196.']
]
---

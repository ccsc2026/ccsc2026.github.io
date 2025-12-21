---
layout: talkpage
categories: [contrib]
talknumber: D3.09
talktime: '12.03.2026, 17:15 – 17:45'
speaker: Prof. Thijs Stuyver
img: 'Stuyver, Thijs.png'
location: 'Paris Sciences et Lettres University · Paris (FR)'
title: "Efficient Exploration of Chemical Reaction Space via Surrogate-Driven Chemical Representations"
authors: 'T. Stuyver, G. Chen, J. E. Alfonso-Ramos'
abstract: [
"The efficient exploration and screening of chemical reaction space requires machine-learning (ML) models capable of making accurate predictions within and across reaction families.[1]
Yet, when only small, high-quality, task-specific datasets are available, conventional ML architectures often suffer from limited accuracy and poor generalizability. 
A common strategy to mitigate this challenge is to augment models with physically motivated quantum-mechanical (QM) descriptors, which has been shown to yield robust, 
data-efficient reactivity predictions—even with only a few hundred training data points.[2,3]
Unfortunately, generating QM descriptors is computationally demanding, limiting the practicality of this approach for truly large-scale or high-throughput screening. Surrogate models that predict descriptors on the fly from molecular graphs offer a promising workaround.[2,3]
Especially when combined with large pre-computed literature QM datasets,[4-6] such surrogates enable generalizable screening pipelines that require minimal task-specific training data and incur only marginal computational cost.
In this talk, I will highlight our recent efforts in this area,[6,7] focusing on results showing that downstream models perform even better when using the surrogate’s internal hidden representations rather than the predicted descriptors — 
except when the descriptor set is tightly aligned with the mechanistic physics of the target reaction class.[7] These latent embeddings from surrogate models encode rich and transferable chemical information, 
making them a powerful foundation for data-efficient predictive chemistry.
Finally, I will briefly discuss ongoing work assessing the benefits of using these pre-trained hidden representations within Bayesian Optimization workflows."]
references: [
['N. Casetti et al.', 'Chem. Eur. J.', '2023', '29', 'e202301957'],
['Y. Guan et al.', 'Chem. Sci.', '2021', '12', '2198-2208'],
['T. Stuyver; C. W. Coley', 'J. Chem. Phys.', '2022', '156', '084104'],
['R. Ramkrishnan et al.', 'Sci. Data', '2014', '1', '1-7'], 
['P. C. St. John et al.', 'Sci. Data', '2020', '7', '244'], 
['J. Alfonso-Ramos; R. Neeser; T. Stuyver', 'Digit. Discov.', '2024', '3', '919-931'], 
['G. Chen; T. Stuyver', 'Digit. Discov.', '2025', '4', '3227-3237']
]
---

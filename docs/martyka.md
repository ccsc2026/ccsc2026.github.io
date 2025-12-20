---
layout: posterpage
categories: [poster]
posternumber: P16
speaker: Mikołaj Martyka
location: 'University of Warsaw · Department of Chemistry · Warsaw (PL)'
title: "Machine Learning Methods for Electronic Excited States: From Foundational Models to Gradient-Free Nonadiabatic Dynamics"
authors: 'M. Martyka, J. Jankowska, P.O. Dral'
abstract: [
"Theoretical photochemistry provides unique insights into complex light-induced phenomena, which are often unobtainable from purely experimental studies. Unfortunately, methods suitable for excited-state simulations come with a steep computational cost, often limiting their applicability in terms of studied systems or level of theory used. However, cutting-edge machine learning (ML) methods allow us to bridge this gap, enabling simulations of larger systems at longer timescales, and using higher-level methods.

The main difficulty in applying machine-learning models to excited states is predicting a complex and correlated manifold of electronic-excited states. To overcome this, we have constructed a novel type of neural network (NN) architecture: a multi-state ANI model (MS-ANI) which is able to learn an arbitrary number of electronic states, with accuracy better than or similar to ground-state predictions. We can couple our proposed state-of-the-art ML model with an efficient active learning (AL) protocol, which is able to learn nonadiabatic molecular dynamics (NAMD) simulations within several days of wall-time. Specifically, employing a physics-informed uncertainty quantification procedure, as well as auxiliary trajectories to map the vicinity of conical intersections, allows us to improve the data-efficiency and robustness of the method.

Finally, we use the MS-ANI architecture as a starting point to build the first-ever foundational model for excited-states properties prediction. This model allows for out-of-the-box predictions of UV-VIS spectra approaching TD-DFT quality, while being faster than semi-empirical methods. Additionally, it can be used as a starting point for fine-tuning models for NAMD simulations, greatly improving their efficiency and stability. This increase in data efficiency allows us to perform fine-tuning, and subsequent dynamics propagation using only energy data, eliminating the computational burden of generating reference gradients. This unlocks access to frontier quantum chemical methods for excited states that lack analytical gradients, such as QD-NEVPT2, enabling excited-state dynamics at previously inaccessible levels of theory"]
---

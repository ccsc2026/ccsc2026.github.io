---
layout: posterpage
categories: [poster]
posternumber: P35
speaker: Dr. Omid Shayestehpour
location: 'Paderborn University · Paderborn (DE)'
title: "Prokyon – An open-source library for on-the-fly machine learning of interatomic potentials"
authors: 'O. Shayestehpour, M. Brehm, H. Elgabarty'
abstract: [
"Machine-learned force fields (MLFFs) have emerged as a transformative tool in computational chemistry, offering a bridge between the high accuracy of ab initio electronic structure methods and the efficiency of classical force fields. By learning the potential energy surface (PES) from quantum mechanical data, these models enable the simulation of complex systems at time and length scales previously deemed inaccessible.

However, a significant challenge remains in the reliability of state-of-the-art models when they encounter under-represented regions of the chemical and configurational space. Static ML models often struggle with extrapolation; when a simulation explores configurations far from the training set, such as transition states, the model may produce unphysical results without warning.

We present Prokyon, an open-source library to provide on-the-fly machine learning force fields to existing electronic structure packages. Prokyon mitigates the risks of extrapolation by implementing active learning workflows based on Bayesian uncertainty quantification.

The library monitors the model’s predictive variance in real-time. Whenever the Bayesian uncertainty falls below a specified confidence threshold, the library triggers an automatic fallback to the underlying electronic structure calculation. This new data point is then used to refine the force field on-the-fly, ensuring that the simulation remains physically grounded even in novel regions of the PES.

Our initial implementation targets CP2K as a primary host package, chosen for its high efficiency in generating reference data. Prokyon is designed for broad interoperability, with future integrations planned for other major codes including ORCA, CPMD, and Quantum Espresso. By providing a standardized interface for adaptive, Bayesian-guided learning, Prokyon aims to make robust, high-fidelity atomistic simulations more accessible to the broader computational chemistry community."]
---

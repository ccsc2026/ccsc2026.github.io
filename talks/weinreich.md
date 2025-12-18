---
layout: talkpage
categories: [contrib]
talknumber: D3.07
talktime: '12.03.2026, 15:15 – 15:45'
speaker: Dr. Jan Weinreich
location: 'Chembricks Inc. · California (USA)'
title: "Beyond the Workhorse: Anchoring DFT with Sparse QMC for Discovery"
authors: 'J. Weinreich'
abstract: [
"DFT is the workhorse of chemical-space exploration: its cost–accuracy balance makes it indispensable for screening and hypothesis generation. However, for some industrial systems, common DFT functionals can misestimate binding energies and - in some cases - invert the relative candidate ranking. Because optimization depends on ranking, these errors can steer discovery away from the best options.
<br><br>
We will present industrial case studies - EDTA-type chelation/mining chemistry and catalysts for metal removal - where DFT underestimates binding energies and produces rank inversions, and compare these results to quantum Monte Carlo (QMC) references. Then we outline a pragmatic workflow that treats DFT as a fast, base-fidelity source, uses sparse QMC anchors as a “truth oracle,” and combines multi-fidelity machine learning with our FastDFT API to enable reliable discovery under real compute budgets. Finally, we pose the operational question: how much beyond-DFT anchoring is needed to ensure trustworthy rankings in practice?"]
---
